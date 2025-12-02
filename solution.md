# Solution Code

<details>
<summary> Step 1 Solution - Add Semantic Structure</summary>
    
HTML - index.html

```html
<header>
  <p>Author Name</p>
</header>

<main>
  <section>
    <!-- Bio Content -->
  </section>

  <section>
    <article>
      <h3>Sample Blog Post 1</h3>
      <p>Brief summary of the first blog post goes here...</p>
      <a href="#">Read more</a>
    </article>
  </section>
</main>

<footer>
  <p>Email: <a href="#">author@example.com</a></p>
</footer>
```

</details>

<details>
<summary>Step 2 Solution – Apply Class Names</summary>

HTML - index.html

```html
<body>
	<div class="page">
	
	<header class="site-header">
	  <h1>Author Name</h1>
	</header>
	
	<main>
	  <section class="bio">
	    <!-- Bio content -->
	  </section>
	
	  <section class="posts">
	    <article class="post-card">
	      ...
	    </article>
	  </section>
	</main>
	
	<footer class="contact">
	  ...
	</footer>
	</div>
</body>
```

</details> 

<details>
<summary>Step 3 Solution – Fix Headings and Bio Content</summary>

HTML - index.html

```html
<h1>Author Name</h1>

<section class="bio">
  <h2>About the Author</h2>
  <img src="http://placehold.co/200x200" alt="Portrait of Author Name">
  <p>This is a short introduction about the author. It may include background, interests, or areas of expertise.</p>
</section>
```

</details>  

<details>

<summary> Step 4 Solution – Standardize Blog Preview Articles</summary>

HTML - index.html

```html
<article class="post-card">
  <h3>How I Got Started in Web Dev</h3>
  <p>A quick look back at my very first line of code...</p>
  <a href="#" class="button">Read more</a>
</article>

<article class="post-card">
  <h3>Top 5 Tools I Use Daily</h3>
  <p>Simple tools that keep my workflow smooth and steady...</p>
  <a href="#" class="button">Read more</a>
</article>

<article class="post-card">
  <h3>Lessons from My First Project</h3>
  <p>Key takeaways from building my first real-world site...</p>
  <a href="#" class="button">Read the full essay</a>
</article>

```

</details>   

<details>

<summary> Step 5 Solution – Contact and Footer Polish</summary>

HTML - index.html

```html
<footer class="contact">
  <a href="mailto:author@example.com" class="button">
    author@example.com
  </a>

  <a href="https://www.linkedin.com/in/yourusername" target="_blank">
    <img 
      src="https://cdn-icons-png.flaticon.com/128/3536/3536505.png" 
      width="24" 
      height="24" 
      alt="LinkedIn icon">
    Follow on LinkedIn
  </a>

  <p>© Your Name</p>
</footer>

```

</details>   

<details>

<summary> Step 6 Solution – Featured Work Section(Optional)</summary>

HTML - index.html

```html
<section class="featured">
  <h2>Featured Work</h2>
  <article class="post-card">
    <h3>My First Portfolio Project</h3>
    <p>A simple site that taught me the basics of HTML, CSS, and sharing my work online...</p>
    <a href="#" class="button">View Project</a>
  </article>
</section>
```
</details>   
 



<details>
 <summary>Final Solution</summary>

HTML - index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Author Bio Page</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="page">

    <!-- ===== Header Area ===== -->
    <header class="site-header">
      <h1>Author Name</h1>
    </header>

    <!-- ===== Main Content ===== -->
    <main>

      <!-- Bio Content -->
      <section class="bio">
        <h2>About the Author</h2>
        <img src="http://placehold.co/200x200" alt="Portrait of Author Name">
        <p>This is a short introduction about the author. It may include their background, interests, or areas of expertise.</p>
      </section>

      <!-- Blog Posts -->
      <section class="posts">
        <article class="post-card">
          <h3>How I Got Started in Web Dev</h3>
          <p>A quick look back at my very first line of code...</p>
          <a href="#" class="button">Read the full essay</a>
        </article>

        <article class="post-card">
          <h3>Top 5 Tools I Use Daily</h3>
          <p>Simple tools that keep my workflow smooth and steady...</p>
          <a href="#" class="button">Read the full essay</a>
        </article>

        <article class="post-card">
          <h3>Lessons from My First Project</h3>
          <p>Key takeaways from building my first real-world site...</p>
          <a href="#" class="button">Read the full essay</a>
        </article>
      </section>

      <!-- Featured Work (Optional) -->
      <section class="featured">
        <h2>Featured Work</h2>
        <article class="post-card">
          <h3>My First Portfolio Project</h3>
          <p>A simple site that taught me the basics of HTML, CSS, and sharing my work online...</p>
          <a href="#" class="button">View Project</a>
        </article>
      </section>

    </main>

    <!-- ===== Footer / Contact ===== -->
    <footer class="contact">
      <a href="mailto:author@example.com" class="button">
        author@example.com
      </a>

      <a href="https://www.linkedin.com/in/yourusername" target="_blank">
        <img 
          src="https://cdn-icons-png.flaticon.com/128/3536/3536505.png" 
          width="24" 
          height="24" 
          alt="LinkedIn icon"
        >
        Follow on LinkedIn
      </a>

      <p>© Your Name</p>
    </footer>
  </div>
</body>
</html>

```
</details>

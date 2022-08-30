---
layout: page
title: About the Purelog Theme
permalink: /about/
---

**Purelog** is a responsive, sidebar theme for the popular JAMstack generator Jekyll that only uses the minimal [**Pure.css** framework](https://github.com/pure-css/pure) (hence the name!), while still following the best practices possible for accessibility and search-engine optimization.

I created this after finishing [Watery](https://github.com/brennanbrown/watery) (which this theme is built off of), as a way to add more functionality and design while still remaining as lightweight as possible.

This project is aimed towards those looking for an interesting theme for Jekyll that has features that aren't found commonly elsewhere, which I'll list down below.

### Features

Here are a few interesting features of this Jekyll theme:

- A fully customizable and empty `_BLANK_config.yml` to make getting up-and-running easy.
- A speedy, on-site search function using [Simply Jekyll Search](https://github.com/christian-fei/Simple-Jekyll-Search).
- Custom collections for different types of material (note-taking, journal writing, etc.)
- An auto-generating archive page that displays all entries from _all_ collections.
- Having a `_pages` collection for easier organization.
- An author bio at the end of each post. (Located in `_inclues/author.html`)
- Full Rouge support for syntax highlighting. (Currently using `base16.solarized.light`)
- Auto-generated RSS feed, sitemap, accessibility features, and search-engine optimization.

<!-- modify this form HTML and place wherever you want your form -->
<form id="my-form" action="https://formspree.io/f/mayknvvk" method="POST">
  <label>Email:</label>
  <input type="email" name="email" />
  <label>Message:</label>
  <input type="text" name="message" />
  <button id="my-form-button">Submit</button>
  <p id="my-form-status"></p>
</form>
<!-- Place this script at the end of the body tag -->
<script>
    var form = document.getElementById("my-form");
    
    async function handleSubmit(event) {
      event.preventDefault();
      var status = document.getElementById("my-form-status");
      var data = new FormData(event.target);
      fetch(event.target.action, {
        method: form.method,
        body: data,
        headers: {
            'Accept': 'application/json'
        }
      }).then(response => {
        if (response.ok) {
          status.innerHTML = "Thanks for your submission!";
          form.reset()
        } else {
          response.json().then(data => {
            if (Object.hasOwn(data, 'errors')) {
              status.innerHTML = data["errors"].map(error => error["message"]).join(", ")
            } else {
              status.innerHTML = "Oops! There was a problem submitting your form"
            }
          })
        }
      }).catch(error => {
        status.innerHTML = "Oops! There was a problem submitting your form"
      });
    }
    form.addEventListener("submit", handleSubmit)
</script>

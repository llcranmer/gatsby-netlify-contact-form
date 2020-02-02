# gatsby-netlify-contact-form
A contact form for Gatsby PWA's deployed on Netlify. 

Download the file and copy it's contents or just copy and paste from here.

```mdx
<form name="contact" method="post" action="/success" data-netlify="true" data-netlify-honeypot="bot-field">
  <input type="hidden" name="bot-field" />
  <input type="hidden" name="form-name" value="contact" />
  <p>
    <label htmlFor="name">Your Name: </label>
    <input type="text" name="name" id="name" />
    <label htmlFor="email">Your Email: </label>
    <input type="text" name="email" id="email" />
  </p>
  <p>
    <label htmlFor="message">Message</label>
    <textarea name="message" id="message" rows="3" style="width: 100%;" />
  </p>
  <p>
    <input type="submit" value="Send Message" className="special" />
    <input type="reset" value="Clear" />
  </p>
</form>

```

If wanting for pure html then try the following.
```html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8" />
<title>HTML5 Doctor | Element Index</title>
<link rel="stylesheet" href="style.css" />
</head>
<body id="home">
<form name="contact" method="post" action="/success" data-netlify="true" data-netlify-honeypot="bot-field">
  <input type="hidden" name="bot-field" />
  <input type="hidden" name="form-name" value="contact" />
  <p>
    <label htmlFor="name">Your Name: </label>
    <input type="text" name="name" id="name" />
    <label htmlFor="email">Your Email: </label>
    <input type="text" name="email" id="email" />
  </p>
  <p>
    <label htmlFor="message">Message</label>
    <textarea name="message" id="message" rows="3" style="width: 100%;" />
  </p>
  <p>
    <input type="submit" value="Send Message" className="special" />
    <input type="reset" value="Clear" />
  </p>
</form>
</body>
</html>
```


## Contributing

Open a PR with changes and if they're verified to work then they'll be merged.

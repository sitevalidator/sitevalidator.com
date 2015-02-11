# Site Validator Static Pages

These are the static pages for Site Validator.

It's built with [middleman](https://middlemanapp.com/), a static site generator.

We use Netlify for continuous deployment and Site Validator for continuous validation, so every time we accept a pull request for this repository the pages will be automatically rebuilt, deployed to http://sitevalidator.com and validated for W3C conformance.

## Running locally

```bash
git clone https://github.com/sitevalidator/sitevalidator.com.git sitevalidator
cd sitevalidator
bundle
middleman server
```

Now you'll be able to view the site at http://localhost:4567/

# ThermoEagle - Ideal Gas Process Calcs

This folder is ready to publish with GitHub Pages.

## Files

- `index.html` — the complete ThermoEagle app with embedded HTML, CSS, and JavaScript.

## Publish on GitHub Pages

1. Create a new GitHub repository, for example `thermoeagle`.
2. Upload `index.html` to the root of the repository.
3. In GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ root**
5. Save and wait for GitHub Pages to publish the site.

Your public URL will look like:

```text
https://YOUR-USERNAME.github.io/thermoeagle/
```

## Canvas iframe embed

In a Canvas Page, Assignment, or Module item that allows HTML editing, use:

```html
<iframe
  src="https://YOUR-USERNAME.github.io/thermoeagle/"
  width="100%"
  height="900"
  style="border: none;"
  loading="lazy">
</iframe>
```

## Notes

This app uses client-side React, Tailwind CSS, and Babel from public CDNs. Because it is a static page, it should work on GitHub Pages, but students will need internet access to load those external libraries.

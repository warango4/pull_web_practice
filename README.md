# Pull web practice

* For contributions with pull requests:
  * The only accepted files are `.html`, `.png` and `.jpg`
  * The only accepted operation is to add files to the repo.
  * The added files with `.html` extension need to have the following elements (element matching the querySelector, with the attribute described, must exist):
```yml 
      - querySelector: "#titulo"
        attribute: textContent
        exists: true
      - querySelector: "#imagen"
        attribute: src
        exists: true
      - querySelector: "#enlace"
        attribute: href
        exists: true
      - querySelector: "#enlace"
        attribute: textContent
        exists: true
```

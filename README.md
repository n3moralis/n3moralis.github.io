# subterranea.dev
 
Source for [subterranea.dev](https://subterranea.dev) — a technical blog documenting a self-built, production-grade hybrid DevSecOps platform.
 
The series covers network segmentation, Zero Trust architecture, Kubernetes hardening, Infrastructure as Code, and a security-focused CI/CD pipeline — built and documented as a two-year project, with each phase validated by penetration testing.
 
## Stack
 
- **Static site generator:** Jekyll
- **Theme:** [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)
- **Hosting:** GitHub Pages + GitHub Actions
- **Diagrams:** Mermaid
## Local development
 
```bash
bundle install
bundle exec jekyll serve --livereload
```
 
The site is then available at `http://localhost:4000`.
 
## License
 
Post content © the author, all rights reserved.
Theme licensed under [MIT](https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/LICENSE).
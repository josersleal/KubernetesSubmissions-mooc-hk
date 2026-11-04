# KubernetesSubmissions
Make sure that the repository is available to the GitHub user mattiluukkainen. We
## Exercises

### Chapter 2

- [1.1.](https://github.com/mluukkai/KubernetesSubmissions/tree/1.1/log_output)
- [1.2.](https://github.com/mluukkai/KubernetesSubmissions/tree/1.2/the_project)
- [1.3.](https://github.com/mluukkai/KubernetesSubmissions/tree/1.3/log_output)
- [1.4.](https://github.com/mluukkai/KubernetesSubmissions/tree/1.4/the_project)
- [1.5.](https://github.com/mluukkai/docker-test/tree/1.5)


# Release instructions

```shel
git add .                             # Stage changes
git commit -m "Exercise 1.1"          # Commit solution
git push origin main                  # Push to GitHub

git tag 1.1                           # Create exercise tag
git push origin 1.1                   # Push tag

gh release create 1.1 --generate-notes  # Create GitHub release
```

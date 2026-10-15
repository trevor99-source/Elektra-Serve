ELEKTRA SERVE WEBSITE - READY FOR GITHUB PAGES

Upload the CONTENTS of this folder (all .html files and .nojekyll). Images are built into every page, so no images folder is needed to the ROOT of your GitHub repository.
The images folder must sit next to index.html, exactly like this:

  index.html  about.html  services.html  portfolio.html  contact.html  appointment-request.html  enquiry-form.html
  images/  (all photos and logos)
  .nojekyll

GitHub steps: repository > Add file > Upload files > drag everything from inside this folder (include the images folder) > Commit.
Then Settings > Pages > Deploy from a branch > main / (root) > Save. Site opens at https://USERNAME.github.io/REPO/ (wait 1-2 minutes).
If images still do not show: the images folder was not uploaded, or it was uploaded inside another folder. File names are case-sensitive on GitHub.

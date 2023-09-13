# whereami

A simple location introspection for GitHub Actions. Each hour a GitHub Action workflow checks to see where in the world it's running from and appends it to `whereami.log`. Location is determined by a free tier [ipstack](https://ipstack.com/) API call.

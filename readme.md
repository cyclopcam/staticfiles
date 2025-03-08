# StaticFiles (Go Package)

staticfiles is a Go package for hosting static files.

- Compresses files and caches the compressed version, so that you get gzipped downloads
- Supports both file system and files embedded in a Go build
- Checks file modification times for development mode, so you don't need to hard refresh your browser
- Understands webpack generated assets with a hash, and gives them very long cache expiration times

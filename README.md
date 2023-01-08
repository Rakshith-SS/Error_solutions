# Quick fixes to a problem I already faced

+ <strong>Viewing Authenticated views even after logging out</strong>

  Able to view authenticated views even after black listing refresh tokens,
  solution reduce the access token lifetime. 

  The frontend should keep requesting for an access token every few minutes.
  To keep a user logged in.

  https://github.com/jazzband/djangorestframework-simplejwt/issues/218


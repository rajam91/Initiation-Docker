docker run -p 80:80 \
  -e POSTGRES_USER=newuser \
  -e POSTGRES_PASSWORD=password \
  -e POSTGRES_HOST=localhost \
  -e POSTGRES_PORT=5432 \
  -e POSTGRES_DB=beautyapp \
  result


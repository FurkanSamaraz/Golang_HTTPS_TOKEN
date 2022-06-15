# Golang_HTTPS_TOKEN

Sertifika oluşturmak için mkcert kullanınız. nss main.go dizininde çalıştırınız.

brew install mkcert

brew install nss 

# if you use Firefox

mkcert localhost

AUTH_USERNAME=alice AUTH_PASSWORD=1234 go run .


https://www.alexedwards.net/blog/basic-authentication-in-go

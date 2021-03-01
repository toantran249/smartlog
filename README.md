## build image

docker build -t Optimization .

## run image

docker run -d -p 8080:8080 Optimazation

## Gọi api với method post cùng url http://localhost:8080/optimization. Body truyền kiểu raw với dữ liệu định dạng json giống với file input.json

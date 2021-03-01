## build image

docker build -t Optimization .

## run image

docker run -d -p 8081:8081 Optimazation

## Gọi api với method post cùng url http://localhost:8081/optimization. Body truyền kiểu raw với dữ liệu định dạng json giống với file input.json

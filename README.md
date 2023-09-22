# opencv-facedetect-demo

A demo use opencv-go library to simple face-detact

```
brew install opencv

echo "export PKG_CONFIG_PATH=\"/usr/local/opt/opencv@4/lib/pkgconfig:$PKG_CONFIG_PATH\"" >> ~/.bashrc  or ~/.zshrc

source ~/.bashrc OR source ~/.zshrc

pkg-config --cflags --libs opencv4

go get -u gocv.io/x/gocv

go mod tidy

go run main.go

```





Refer: 
https://mp.weixin.qq.com/s/Vpjeu_JSvgvu6_ExiyKxTg

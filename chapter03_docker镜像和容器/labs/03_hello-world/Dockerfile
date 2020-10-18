# 不用base image，从0开始做一个镜像
FROM scratch

# 把hello二进制程序，加到根目录
# 注意hello程序必须是从静态库编译的 gcc -o hello -static hello.c
ADD hello /
CMD ["/hello"]


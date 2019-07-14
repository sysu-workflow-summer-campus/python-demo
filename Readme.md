# Python操作kubernetes示例

## 使用方法

在云主机上运行一下命令：

```(bash)
pip install -r requirements.txt
python main.go
```

## 注意事项

- 运行前，您需要先设置环境变量`KUBERNETES_SERVICE_HOST`为`kubernetes.default`，设置`KUBERNETES_SERVICE_PORT`为`443`

- 由于该方法需要运行在集群内部的pod才可以运行，所以本地执行并不能达到您所期望的效果

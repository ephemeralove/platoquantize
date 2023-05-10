# platoquantize
lenet5量化：
(win):
python run.bat -c configs\MNIST\fedavg_lenet5_quantize.yml
(linux):
./run -c configs\MNIST\fedavg_lenet5_quantize.yml

resnet量化：
(win):
python run.bat -c configs\CIFAR10\fedavg_resnet18_quantize.yml
(linux):
./run -c configs\CIFAR10\fedavg_resnet18_quantize.yml

fedasync:
python examples/fedasync/fedasync.py -c examples\fedasync\fedasync_CIFAR10_resnet18quantize.yml
python examples/fedasync/fedasync.py -c examples\fedasync\fedasync_MNIST_lenet5quantize.yml


# 定义编译器
CXX = g++

# 定义包含路径
INCLUDE_DIRS = -I"D:\software\boost_1_85_0" -I.

# 定义源文件
SRCS = test.cpp

# 定义目标可执行文件
TARGET = tes

# 默认目标
all: $(TARGET)

# 编译规则
$(TARGET): $(SRCS)
	$(CXX) $(INCLUDE_DIRS) $(SRCS) -o $(TARGET)

# 清理规则
clean:
	rm -f $(TARGET).exe
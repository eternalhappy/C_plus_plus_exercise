# 编译器
CXX = g++

# 编译选项
CXXFLAGS = -Wall -g

# 目标文件
TARGET = student_management

# 源文件
SRCS = studentmain.cpp student.cpp

# 依赖文件
DEPS = student.h

# 生成目标
$(TARGET): $(SRCS) $(DEPS)
    $(CXX) $(CXXFLAGS) -o $(TARGET) $(SRCS)

# 清理
clean:
    rm -f $(TARGET)

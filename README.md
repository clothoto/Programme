# 定义一个函数来计算平方
def calculate_square(num):
    return num * num

# 主程序
if __name__ == "__main__":
    # 输入一个数字
    num = float(input("请输入一个数字："))
    
    # 调用函数计算平方
    result = calculate_square(num)
    
    # 输出结果
    print(f"{num} 的平方是 {result}")

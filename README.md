
## 概述

理发店会员管理系统是一个基于Microsoft Foundation Classes (MFC) 的桌面应用程序，旨在帮助理发店高效地管理会员信息。该系统提供了会员信息的增加、删除、修改和查询功能，以及会员余额的充值和扣费操作。

## 功能特点

- **会员信息管理**：系统允许用户添加、删除和修改会员的基本信息，包括手机号、姓名、性别、余额和会员等级。
- **余额操作**：提供会员余额的充值和消费扣费功能。
- **信息查询**：支持通过手机号查询会员的详细信息。
- **数据持久化**：系统支持将会员数据保存到文件中，并从文件中加载数据。

## 技术栈

- **编程语言**：C++
- **开发框架**：Microsoft Foundation Classes (MFC)
- **数据存储**：文本文件（.txt）

## 系统要求

- 操作系统：Windows
- 编译器：Microsoft Visual C++ 或更高版本

## 安装与运行

1. 打开Visual C++开发环境。
2. 导入项目文件 `Barershop member management system2.vcxproj`。
3. 根据需要配置项目属性。
4. 编译并运行项目。

## 使用说明

- 启动应用程序后，主界面将显示会员列表。
- 使用按钮进行会员信息的增加、删除、修改和查询操作。
- 点击“打开文件”按钮加载会员数据。
- 点击“保存”按钮将当前会员数据保存到文本文件中。

## 文件结构

- `Barershop member management system2.cpp` 和 `.h`：主应用程序类文件。
- `ChildDlg.cpp` 和 `.h`：会员信息编辑对话框类文件。
- `Datainterface.cpp` 和 `.h`：数据访问接口，负责数据的读写操作。
- `Cinfo.h` 和 `.cpp`：会员信息类，定义了会员数据结构。
- `resource.h`：资源文件，包含项目的所有资源定义。
- `ReadMe.txt`：本文档。
## 部分截屏
![image](https://github.com/user-attachments/assets/3d7b11ca-b8e9-4656-91ad-05117304abda)
![image](https://github.com/user-attachments/assets/01ffc05c-d5bf-48aa-a0d3-21148f4ec05a)
![image](https://github.com/user-attachments/assets/4c35f830-f754-4a49-b306-b114fdc783dc)
## 注意事项

- 确保所有输入的手机号为11位数字。
- 充值和扣费操作前，请确保会员余额充足。
- 保存数据前，请确认所有输入信息准确无误。

## 版本历史

- v1.0.0：初始版本，实现了基本的会员管理功能。

## 许可

本项目采用[MIT许可](https://opensource.org/licenses/MIT)进行许可。


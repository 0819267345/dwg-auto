# dwg-auto
自动转图纸工具 v1.0 功能：读取多个DWG文件，根据Excel数据按零件厚度(mm)分组，统一排版到一个DXF文件中 依赖：pip install ezdxf pandas openpyxl 说明：   - 输出为DXF格式，AutoCAD可直接打开并另存为DWG   - 如需自动输出DWG，需安装AutoCAD并勾选"自动转DWG"选项   - DWG读取依赖ezdxf内置解析器，支持大多数2D图纸

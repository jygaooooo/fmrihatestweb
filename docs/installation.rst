安装
====

这一页只演示文档写法，不要求你真的发布一个 Python 包。

第一步，创建虚拟环境::

   python -m venv .venv

第二步，激活虚拟环境。

如果你是 macOS 或 Linux：

   source .venv/bin/activate

如果你是 Windows PowerShell：

   .venv\Scripts\Activate.ps1

第三步，安装依赖::

   python -m pip install -r requirements.txt

说明：

- 这个玩具示例只依赖 Sphinx。
- Sphinx 会把这些 .rst 文件转换成 HTML 页面。

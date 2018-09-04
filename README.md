fork from https://github.com/enjoiz/XXEinjector

在kali中运行XXEinjector时发现代码中的:
`Thread.current.report_on_exception = false`
这句有问题,导致XXEinjector无法在kali(2018)中顺利运行,当前项目将原作者代码中的这行代码注释了(大约14处).也即变成:
`#Thread.current.report_on_exception = false`

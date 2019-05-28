
131 G,  131 gg          定位到行
viwy/viwp           拷贝、覆盖粘贴一个单词
dw,  yw, cw, vw  
vi(      di(    ci(    yi(

shift  +  ~                     toggle toUpperCase/lowerCase
U             upperCase
u             lowerCase
shift + j               join lines
tabn + 5,   5gt           switch to tab 5
df}, dt}            删除直到包括（不包括）”｝”
d$，D              delete to end of line
d0, d^              delete to beginning of line (character)
:1,.d             delete to beginning of file
:.,$d             delete to end of file
set buftype: " "          E382: Cannot write, 'buftype' option is set
:so(urce) ~/.vimrc        设置立即生效
''              跳转到光标上次停靠的地方, 是两个', 而不是一个"  
*               在文件中向前搜索当前光标所在的单词 
#               在文件中向后搜索当前光标所在的单词

10>>              10行往右移动
vat/vit             html dom tag 块
tabc              关闭 tab
noh/nohl            no high light


替换
https://www.cnblogs.com/fakis/archive/2010/07/17/1976595.html
:m,ns/str1/str2/g         将 m 行到 n 行中的字串 str1 全部替换为字串 str2。
:%s/str1/str2/g             全文替换
块操作:
Ctrl+v, 选中行，I（大写I）, #, ESC


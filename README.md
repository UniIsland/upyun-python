# upyun-python

python upyun sdk

i simply downloaded the original sdk on upyun.com and wrote a pip package. no code modified so far, will do later.
http://static.b0.upaiyun.com/upyunapi/upyun-python-api.zip

## Installation

pip install -e git://github.com/UniIsland/upyun-python.git#egg=upyun-python

## Usage

	>>> from upyun import UpYun
	>>> u = UpYun('空间名称','操作员用户名','操作员密码')
	>>> filelist = u.readDir('/foo/')
	>>> for file in filelist:
	>>> 	print file.filename
	foo.txt
	bar.txt

see docs/test.py for more examples


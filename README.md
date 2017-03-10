# python-youku-genuine-pig
爬虫抓视频  [好吧 是我无聊想趴点东西 国外看优酷始终有问题 没办法]

import urllib2
response = urllib2.urlopen(url)
content = urllib2.urlopen(url).read()
print "response headers:", response.headers
print "content:", content
##此时 comment 里面已经有你想要的所有东西了 但是我们也得做点筛选不是  


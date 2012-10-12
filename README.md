aliosspy
========

Aliyun OSS Python SDK

client = alioss.Client('your-access-key-id', 'your-access-key-secret', 'bucket_name')
client.put_object('path/to/hello.html', '<h1>file content</h1>')
# http url of object

print client.get_object('path/to/hello.html')

client.delete_object('path/to/hello.html')


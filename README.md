# shout_cloud.py
Web-API for [shoutcloud.io](http://shoutcloud.io) all caps as a service

## Example
```python
from shout_cloud import ShoutCloud

s_cloud = ShoutCloud()
capitalized_text = s_cloud.capitalize_text(text="example")
print(capitalized_text)
```

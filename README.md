# django-response
Django Response Relative

## Installation
```shell
pip install django-response
```

## Usage
```python
from django_response import response

def xxx(request):
    # return response()
    # return response(XXXStatusCode.YYY)
    return response(200, 'message', u'description', data={})
```



```
def generate_date_range_list(start_date_str, end_date_str):
    try:
        start_date = datetime.datetime.strptime(start_date_str, "%Y-%m-%d")
        end_date = datetime.datetime.strptime(end_date_str, '%Y-%m-%d')
        step = datetime.timedelta(days=1)
        result = []
        while start_date<=end_date:
            result.append(str(start_date.date()))
            start_date+=step
        return result
    except Exception,e:
        print str(e)
```

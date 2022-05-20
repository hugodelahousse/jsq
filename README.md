# JSQ aka JavaScript Query

```
$ jsq 'input.elements.flapMap(e => e.values).filter(v => v > 3).slice(0, 5)' elements.json


$ curl -X GET "https://httpbin.org/json" -H "accept: application/json" | jsq 'input.slideshow.slides.map(s => s.title)'
```

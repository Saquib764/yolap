# yolap

`Description :` Its a group of `Polymer` elements for tyeahead, selecting tags and showing tags.

1. Install using bower: 
```script
bower install yolap
```
2. Import `yolap.html` to import all Yolap Polymer elements.

# Basics
Yolap have two categories of elements, i.e `tag viewers and removers` and `tag creators`.

1. Tag viewers and removers.
Every tags views have a unique tag creator linked with it. It gets all added tags from it and displays. You can remove tags via remove action. Example:
```script
<yolap-view-tags icon='close' from='<some creators id>'></yolap-view-tags>
```

2. Tag creators
These elemnents need an array of items from which tags will be selected. It takes a query as input and display a list of matched item. It have a filter attribute that allows control over match with input query. Example: 

```script
<yolap-click-addtag id='in' filters='null'></yolap-click-addtag>
```

Feed the list of data that need to be displayed.
```script
document.querySelector('#in').data = [{
            name: 'India'
        },{
            name: 'Indiana'
        },{
            name: 'Maharastra'
        }]
```


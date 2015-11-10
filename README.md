# yolap

`Description :` Its a group of `Polymer` elements for tyeahead, selecting tags and showing tags.

1. Install using bower: 
```script
bower install yolap
```
2. Import `yolap.html` to import all Yolap Polymer elements.

3. Attributes
All Yolap elements share few common attributes, `key, filters`

# List of Yolap Polymer elements
1. yolap-click-addtag
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

# pytracing
a python trace profiler that outputs to chrome trace-viewer format (about://tracing).

# usage

    from pytracing import TraceProfiler
    tp = TraceProfiler(output=open('/tmp/trace.out', 'wb'))
    with tp.traced():
      ...execute something here...

# screenshots

## click to view detail

![click to view detail](http://kwlzn.github.io/img/pytracing-screenshots/screen1.png "click to view detail")


## selection and aggregate view

![selection and aggregate view](http://kwlzn.github.io/img/pytracing-screenshots/screen2.png "selection and aggregate view")


## zooming

![zoom](http://kwlzn.github.io/img/pytracing-screenshots/screen3.png "zoom")

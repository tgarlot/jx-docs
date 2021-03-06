---
date: 2018-10-06T10:44:53Z
title: "jx gc"
slug: jx_gc
url: /commands/jx_gc/
---
## jx gc

Garbage collects Jenkins X resources

### Synopsis

Garbage collect resources
  
  Valid resource types include:
  
  * activities  
  * helm  
  * previews  
  * releases

```
jx gc TYPE [flags]
```

### Examples

```
  jx gc previews
  jx gc activities
  jx gc helm
  jx gc gke
  jx gc previews
  jx gc releases
```

### Options

```
  -h, --help   help for gc
```

### SEE ALSO

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X
* [jx gc activities](/commands/jx_gc_activities/)	 - garbage collection for activities
* [jx gc gke](/commands/jx_gc_gke/)	 - garbage collection for gke
* [jx gc helm](/commands/jx_gc_helm/)	 - garbage collection for Helm ConfigMaps
* [jx gc previews](/commands/jx_gc_previews/)	 - garbage collection for preview environments
* [jx gc releases](/commands/jx_gc_releases/)	 - garbage collection for Releases

###### Auto generated by spf13/cobra on 6-Oct-2018

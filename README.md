

cookie_([cname [, cvalue [, settings]]])
  getter/setter

	.alter(cmap)
	  set cookie to match @cmap

	.clear()
	  deletes all cookies

	.each(callback [, context])
	  loops cookie k/v pairs

	.fetch([cname])
	  getter

	.has([cname])
	  tests if cookie cname is set

	.len()
	  counts #of cookies set

	.ls()
	  gets set cookie names

	.rm(cname)
	  removes a cookie

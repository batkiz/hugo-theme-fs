+++
date = "2021-02-01T20:56:06+08:00"
title = "markdown"
tags = ["markdown", "math"]
katex = true
+++

Lid est laborum et dolorum fuga. Et harum quidem rerum facilis est et expeditasi distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihilse impedit quo minus id quod amets untra dolor amet sad. Sed ut perspser iciatis unde omnis iste natus error sit voluptatem accusantium doloremque laste. Dolores sadips ipsums sits.

# Heading 1

Lid est laborum et dolorum fuga. Et harum quidem rerum facilis est et expeditasi distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihilse impedit quo minus id quod amets untra dolor amet sad. Sed ut perspser iciatis unde omnis iste natus error sit voluptatem accusantium doloremque laste. Dolores sadips ipsums sits.

## Heading 2

Lid est laborum et dolorum fuga. Et harum quidem rerum facilis est et expeditasi distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihilse impedit quo minus id quod amets untra dolor amet sad. Sed ut perspser iciatis unde omnis iste natus error sit voluptatem accusantium doloremque laste. Dolores sadips ipsums sits.

### Heading 3

Lid est laborum et dolorum fuga. Et harum quidem rerum facilis est et expeditasi distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihilse impedit quo minus id quod amets untra dolor amet sad. Sed ut perspser iciatis unde omnis iste natus error sit voluptatem accusantium doloremque laste. Dolores sadips ipsums sits.

#### Heading 4

Lid est laborum et dolorum fuga. Et harum quidem rerum facilis est et expeditasi distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihilse impedit quo minus id quod amets untra dolor amet sad. Sed ut perspser iciatis unde omnis iste natus error sit voluptatem accusantium doloremque laste. Dolores sadips ipsums sits.

##### Heading 5

Lid est laborum et dolorum fuga. Et harum quidem rerum facilis est et expeditasi distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihilse impedit quo minus id quod amets untra dolor amet sad. Sed ut perspser iciatis unde omnis iste natus error sit voluptatem accusantium doloremque laste. Dolores sadips ipsums sits.

###### Heading 6

Lid est laborum et dolorum fuga. Et harum quidem rerum facilis est et expeditasi distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihilse impedit quo minus id quod amets untra dolor amet sad. Sed ut perspser iciatis unde omnis iste natus error sit voluptatem accusantium doloremque laste. Dolores sadips ipsums sits.

## Typography

Lid est laborum et dolorum fuga, This is [an example](http://example.com/ "Title") inline link. Et harum quidem rerum facilis, **This is bold** and _emphasis_ cumque nihilse impedit quo minus id quod amets untra dolor amet sad. While this is `code block()` and following is a `pre` tag

    print 'this is pre tag'

Following is the syntax highlighted code block

```go
func getCookie(name string, r interface{}) (*http.Cookie, error) {
	rd := r.(*http.Request)
	cookie, err := rd.Cookie(name)
	if err != nil {
		return nil, err
	}
	return cookie, nil
}

func setCookie(cookie *http.Cookie, w interface{}) error {
	// Get write interface registered using `Acquire` method in handlers.
	wr := w.(http.ResponseWriter)
	http.SetCookie(wr, cookie)
	return nil
}
```

math here: $\sum_{i=1}^n a_i=0$

$$f(x_1,x_x,\ldots,x_n) = x_1^2 + x_2^2 + \cdots + x_n^2$$

$$
f(x)= ∑_{k=0}^{∞} \frac{ f^{(k)}(x_0)}{n!} \left( x-x_0 \right)^k
$$

$$\varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }$$


This is blockquote, Will make it _better now_

> 'I want to do with you what spring does with the cherry trees.' <cite>cited ~Pablo Neruda</cite>\*

> Et harum quidem _rerum facilis_ est et expeditasi distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihilse impedit

Unordered list

- Red
- Green
- Blue

Ordered list

1. Red
2. Green
3. Blue

---
layout: post
title: "HEEEEEEEEEEEEEEEEEEELO WORLD"
date: 2013-11-14
---

# H1

## H2

### H3

fooooooooooooo baaaaaaaaaaaaaaaar

[link to a post]({{ site.baseurl }}{% post_url 2013-11-14-hello-world %})

[link to a resource]({{ "assets/resource_file.txt" | absolute_url }})

```python
def foo(*args, **kwargs):
	print("Jekyll 2 starts supporting Redcarpet 2")
```

{% highlight python linenos=inline %}
def foo(*args, **kwargs):
	print("Jekyll 2 starts supporting Redcarpet 2")
{% endhighlight %}

```cpp
constexpr decltype(auto) foo(int x, auto (*y)(double, char) -> auto (&)(unsigned) -> float){
	if(y != nullptr){
		auto func = [x](auto param1, auto &&param2) noexcept -> decltype(x + param1 + param2){
			return x + param1 + param2;
		}
		return static_cast<std::intptr_t>(func(x, 1, 2));
	}
	return static_cast<std::intptr_t>(static_cast<const char *>((
		"Jekyll's own code highlighting syntax is recommend", 
		"Since this would allow Jekyll to render it with more infomation."
	)));
}
```

{% highlight cpp linenos %}
constexpr decltype(auto) foo(int x, auto (*y)(double, char) -> auto (&)(unsigned) -> float){
	if(y != nullptr){
		auto func = [x](auto param1, auto &&param2) noexcept -> decltype(x + param1 + param2){
			return x + param1 + param2;
		}
		return static_cast<std::intptr_t>(func(x, 1, 2));
	}
	return static_cast<std::intptr_t>(static_cast<const char *>((
		"Jekyll's own code highlighting syntax is recommend", 
		"Since this would allow Jekyll to render it with more infomation."
	)));
}
{% endhighlight %}
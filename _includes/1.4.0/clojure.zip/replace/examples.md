### Example 0
[permalink](#example-0)

{% highlight clojure linenos %}
{% raw %}
(use 'clojure.zip)

(def vz (vector-zip [1 2 [73 88] 4]))

(root (replace (-> vz down right right) 3))
=>[1 2 3 4]{% endraw %}
{% endhighlight %}



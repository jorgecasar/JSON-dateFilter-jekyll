JSON dateFilter jekyll
======================

A Liquid tag filter for Jekyll to filter array by date using chronic syntax. It's very usefull to filter posts, pages or data from JSON to get only the items of last month, before today or whatever.

# Usage

{% json_filter result from source where attribute operator condition %}
 
# Example

{% json_filter old_post from posts where date >= 1 year ago %}

This is a real example: http://jorgecasar.github.io/talks/ And you can show the source code here: https://github.com/jorgecasar/jorgecasar.github.io/blob/source/source/talks/index.html

# Dependencies

- [chronic](https://github.com/mojombo/chronic)
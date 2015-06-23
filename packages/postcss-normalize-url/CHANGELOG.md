# 2.0.2

* Addresses an issue where relative path separators were converted to
  backslashes on Windows.

# 2.0.1

* Documentation/metadata tweaks for plugin guidelines compatibility.
* Bump css-list to 0.1.0, use instead of postcss.list.space for namespace
  rule normalization.

# 2.0.0

* Improved URL detection when using two or more in the same declaration.
* node 0.10 is no longer supported.

# 1.2.1

* Patch to address incorrect transformation of `@document` rules.

# 1.2.0

* Fixes an issue where options could not be passed through.
* Support for normalising URLs in `@namespace` rules.

# 1.1.0

* Now uses the PostCSS `4.1` plugin API.

# 1.0.2

* Adds a JSHint config, code tidied up.

# 1.0.1

* Bug fix; does not transform embedded base 64 or svg images.

# 1.0.0

* Initial release.
# This text is rather big!
## This text is smaller.
###### This text is tiny.

![Image of a cat](https://breed-assets.wisdompanel.com/cat/domestic-cat-finland/European_Domestic.png)

Random excerpt of code from a project:
```gdscript
# Temporary variables to store number as a string
	var n_temp = ""
	var a_temp = ""
	# Delete farthest characters from rightmost numeric and aemic pools (unless SDs say otherwise)
	if (numeric_pool[-1] != null):
		n_temp = str(numeric_pool[-1])
		if (not farthest_dplace(numeric_pool[-1]) < significantDecimals[-1]):
			n_temp = n_temp.erase(n_temp.length() - 1, 1)
	if (aemic_pool[-1] != null):
		a_temp = str(aemic_pool[-1])
		if (not farthest_dplace(aemic_pool[-1]) < significantDecimals[-1]):
			a_temp = a_temp.erase(a_temp.length() - 1, 1
```

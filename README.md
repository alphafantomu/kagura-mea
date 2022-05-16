# kagura-mea
A lightweight async function binder, named after only the most loved virtual youtuber, Kagura Mea.

# Installation
Luvit and lit need to be installed in your system, to install kagura-mea please run the following command:
```bash
lit install alphafantomu/kagura-mea
```

# Usage
The library returns a function which will be used to bind to synchronous functions, like so:
```lua
local async = require('kagura-mea');

local fx = async(function(n)
	return n * 5;
end);

print(fx());

fx(function(err, n)
	assert(not err, err);
	print(n);
end);
```

# Kagura Mea
You can find her socials here:
- [Youtube](https://www.youtube.com/channel/UCWCc8tO-uUl_7SJXIKJACMw)
- [Twitter](https://twitter.com/KaguraMea_VoV)
- [Bilibili](https://space.bilibili.com/349991143)
- [Her Merchanise](https://kaguramea.booth.pm/)
- [Her Tip](https://streamlabs.com/kaguramea0x0/tip)

# Disclaimer
There are no affiliations with Kagura Mea involved.

# License
[MIT License](/LICENSE)

# Contact
- Discord: `Arivistraliavatoriar#2678`
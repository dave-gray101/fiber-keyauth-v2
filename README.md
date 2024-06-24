
# fiber keyauth v3 -> v2 backport

I needed to extend the fiber keyauth middleware to support multiple key sources. These changes were contributed to fiber upstream for the next v3 version [in this pr](https://github.com/gofiber/fiber/pull/3028). As my project still depends on v2 for the time being, this repo hosts a minimally-backported version for all to use
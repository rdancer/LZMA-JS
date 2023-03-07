lzma-d-sync.min.js: lzma-d-sync.js
	uglifyjs $< -o $@ -c -m
	echo compressed size: `wc -c $@ | awk '{ printf "%.2f", $$1 / 1024 }'`kB

.PHONY: clean
clean:
	rm -f *.min.js
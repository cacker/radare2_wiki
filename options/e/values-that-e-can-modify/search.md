<!-- TITLE: search -->

# search

- **`search.align`** Only catch aligned search hits _Default is 0_
- **`search.chunk`** Chunk size for /+ (default size is asm.bits/8 _Default is 0_
- **`search.contiguous`** Accept contiguous/adjacent search hits _Default is true_
- **`search.distance`** Search string distance _Default is 0_
- **`search.esilcombo`** Stop search after N consecutive hits _Default is 8_
- **`search.flags`** All search results are flagged, otherwise only printed _Default is true_
- **`search.from`** Search start address _Default is 0xffffffffffffffff_
- **`search.in`** Specify search boundaries _Default is io.maps_
	> Example: `e search.in = dbg.maps`
	{.is-info}

	> To see available options, use `e search.in=?` Available sections are:
			- raw
			- block
			- io.map
			- io.maps
			- io.sections
			- io.sections.write
			- io.sections.exec
			- io.sections.readonly
			- dbg.stack
			- dbg.heap
			- dbg.map
			- dbg.maps
			- dbg.maps.exec
			- dbg.maps.write
			- dbg.maps.readonly
			- anal.fcn
			- anal.bb


- **`search.kwidx`** Store last search index count _Default is 0_
- **`search.maxhits`** Maximum number of hits (0 _Default is 0_
- **`search.overlap`** Look for overlapped search hits _Default is false_
- **`search.prefix`** Prefix name in search hits label _Default is hit_
- **`search.show`** Show search results _Default is true_
- **`search.to`** Search end address _Default is 0xffffffffffffffff_

<p hidden>search.align search.chunk search.contiguous search.distance search.esilcombo search.flags search.from search.in search.kwidx search.maxhits search.overlap search.prefix search.show search.to</p>
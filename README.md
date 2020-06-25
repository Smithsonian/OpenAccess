# OpenAccess
### Smithsonian Open Access Metadata Repository (GitHub)

- Over 11 million metadata records from the Smithsonian Institution
- Files are serialized as [line-delimited JSON](https://en.wikipedia.org/wiki/JSON_streaming#Line-delimited_JSON) and compressed into bzip2 format
- Directories are organized by owning unit and files are distributed by first two characters of content serialization hash.

------------

	metadata
		objects/ACM
			00.txt.bz2
			...
			0a.txt.bz2
		objects/SAAM
			e3.txt.bz2

More information about Open Access at the Smithsonian as well as documentation on metadata schemas can be found at https://si.edu/openaccess and https://edan.si.edu/openaccess/docs/

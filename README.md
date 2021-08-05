# OpenAccess

## Smithsonian Open Access Metadata Repository (GitHub)


-!! Maintenance Note.. We are transitioning away from GitHub for our compressed archive.. 
 All resouces will be transitioned to S3 by Spetember 1st, 2021... Please revisit us then
 to receive updates on how to pull new resources..

- Over 11 million metadata records from the Smithsonian Institution.
- Files are serialized as [line-delimited
  JSON](https://en.wikipedia.org/wiki/JSON_streaming#Line-delimited_JSON) and
  compressed with [bzip2](https://en.wikipedia.org/wiki/Bzip2).
- Directories are organized by owning unit and files are distributed by first
  two characters of content serialization hash.

---

```
metadata
        objects/ACM
                00.txt.bz2
                ...
                0a.txt.bz2
        objects/SAAM
                e3.txt.bz2
```

Owning units are internal Smithsonian acronyms.

Code | Description
--- | ---
AAA | Archives of American Art
ACM | Anacostia Community Museum
CFCHFOLKLIFE | Ralph Rinzler Folklife Archives and Collections
CHNDM | Cooper Hewitt, Smithsonian Design Museum
EEPA | Eliot Elisofon Photographic Archives
FBR | Smithsonian Field Book Project
FSG | Freer Gallery of Art and Arthur M. Sackler Gallery
HAC | Smithsonian Gardens
HMSG | Hirshhorn Museum and Sculpture Garden
HSFA | Human Studies Film Archives
NAA | National Anthropological Archives
NASM | National Air and Space Museum
NMAAHC | National Museum of African American History and Culture
NMAH | National Museum of American History
NMAI | National Museum of the American Indian
NMAfA | National Museum of African Art
NMNH | National Museum of Natural History
NMNHANTHRO | NMNH - Anthropology Dept.
NMNHBIRDS | NMNH - Vertebrate Zoology - Birds Division
NMNHBOTANY | NMNH - Botany Dept.
NMNHEDUCATION | NMNH - Education & Outreach
NMNHENTO | NMNH - Entomology Dept.
NMNHFISHES | NMNH - Vertebrate Zoology - Fishes Division
NMNHHERPS | NMNH - Vertebrate Zoology - Herpetology Division
NMNHINV | NMNH - Invertebrate Zoology Dept.
NMNHMAMMALS | NMNH - Vertebrate Zoology - Mammals Division
NMNHMINSCI | NMNH - Mineral Sciences Dept.
NMNHPALEO | NMNH - Paleobiology Dept.
NPG | National Portrait Gallery
NPM | National Postal Museum
NZP | Smithsonian's National Zoo & Conservation Biology Institute
SAAM | Smithsonian American Art Museum
SIA | Smithsonian Institution Archives
SIL | Smithsonian Libraries

More information about Open Access at the Smithsonian as well as documentation
on metadata schemas can be found at <https://www.si.edu/openaccess> and
<https://edan.si.edu/openaccess/docs/>.

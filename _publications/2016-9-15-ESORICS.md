---
title: "An Efficient Non-interactive Multi-client Searchable Encryption with Support for Boolean Queries"
collection: publications
category: conferences
permalink: /publication/2016-ESORICS
excerpt: ' '
date: 2016-9-15
venue: 'ESORICS 2016'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-319-45744-4_8'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Shifeng Sun, Joseph K. Liu, Amin Sakzad, Ron Steinfeld, Tsz Hon Yuen: An Efficient Non-interactive Multi-client Searchable Encryption with Support for Boolean Queries. ESORICS (1) 2016: 154-172'

---
Motivated by the recent searchable symmetric encryption protocol of Cash et al., we propose a new multi-client searchable encryption protocol in this work. By tactfully leveraging the RSA-function, our protocol avoids the per-query interaction between the data owner and the client, thus reducing the communication overhead significantly and eliminating the need of the data owner to provide the online services to clients at all times. Furthermore, our protocol manages to protect the query privacy of clients to some extent, meaning that our protocol hides the exact queries from the data owner. In terms of the leakage to server, it is exactly the same as Cash et al., thus achieving the same security against the adversarial server. In addition, by employing attribute-based encryption technique, our protocol also realizes the fine-grained access control on the stored data. To be compatible with our RSA-based approach, we also present a deterministic and memory-efficient ‘keyword to prime’ hash function, which may be of independent interest.

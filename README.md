# Lukas Scheucher

Engineer. Former founder. Currently tinkering with what tiny language models can do — like [ng-video-lecture](https://github.com/scheuclu/ng-video-lecture), a char-level transformer I trained from scratch on a single GPU and [shipped as a static webpage](https://scheuclu.github.io/ng-video-lecture) that runs inference entirely in your browser.

More recently, [language-drift](https://github.com/scheuclu/language_drift): thirteen yearly Word2Vec models trained on a billion tokens of Common Crawl each, aligned with orthogonal Procrustes so the same word has thirteen comparable positions across 2013–2025, then [visualized in your browser](https://language-drift.vercel.app). The interesting bit — you can't compare cosines across two independently-trained Word2Vec models, because each one lives in its own rotated coordinate system. The rotation that aligns them is what makes the drift signal visible.

- remove black border to form initial crop box using 8x reduced image and default threshold
- reduce cropbox to 80% and crop full jpeg to produce tmp image for deskew
- calculate threshold and bitonalize
- run text deskew algorithm
- if text deskew confidence is low, calculate edge deskew
- deskew full jpg using calculated angle
- find binding crop
- find clean crop lines
- write output
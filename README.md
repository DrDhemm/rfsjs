# RFSjs

RFS but in js

- Where this thing come from
  - Originally this RFS just JS version of this [RFS](https://www.npmjs.com/package/rfs)
  - The one who convert this is [supposedly](https://gist.github.com/supposedly)
  - The original JS converted source code is from [here](https://gist.github.com/supposedly/9b9f5de66c2bcbbf5d7469dcec50bfd7)
  - And i'm only publish this to npm, so it's easy to import (my first intention is for using it in my project)
- Use case
  - For me personally, using it with styled-components, since it don't support PostCSS
- Usage

  - Minimal usage (mostly for me atleast) example

    ```
    import styled from "styled-components"
    import rfs from "rfsjs"

    const Heading = styled.h1`
        color: #4d4d4d;
        font-weight: bold;
        ${rfs("4rem", "font-size")}
    `;
    ```

## Credit
- Licensed under MIT [(RFS)](https://github.com/twbs/rfs/blob/master/LICENSE):
- Copyright (c) 2017-2019 Martijn Cuppens
- Copyright (c) 2020 Hadi Tarhini
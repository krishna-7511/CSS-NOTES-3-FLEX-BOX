flex-direction: row;              /* Default - horizontal left to right */
flex-direction: row-reverse;      /* Horizontal right to left */
flex-direction: column;           /* Vertical top to bottom */
flex-direction: column-reverse;   /* Vertical bottom to top */


nowrap (default) → All flex items stay in a single line, even if they overflow.
wrap → Flex items wrap onto the next line if they don’t fit.
wrap-reverse → Like wrap, but items wrap in the reverse direction.

flex-wrap: nowrap;                /* Default - no wrapping */
flex-wrap: wrap;                  /* Items wrap to the next line */
flex-wrap: wrap-reverse;          /* Items wrap in reverse order */

justify-content: flex-start;      /* Default - start of the container */
justify-content: flex-end;        /* End of the container */
justify-content: center;          /* Center of the container */
justify-content: space-between;   /* Space between items */
justify-content: space-around;    /* Space around items */
justify-content: space-evenly;    /* Even space between items */

justify-content tells how the browser distributes space between and around content items along the main axis

align-items: stretch;             /* Default - stretch to fill the container */
align-items: flex-start;          /* Align to start */
align-items: flex-end;            /* Align to end */
align-items: center;              /* Align to center */
align-items: baseline;            /* Align by text baseline */

align-items distributes our items along the cross axis


align-content: stretch;           /* Default - stretches items */
align-content: flex-start;
align-content: flex-end;
align-content: center;
align-content: space-between;
align-content: space-around;

align-content it sets the distribution of space between and arond content items along a flexbox's cross-axis



Properties of Flex Items:

flex-grow: 1;                     /* Item can shrink if needed  along the flexitem */
flex-shrink: 1;                   /* Item can shrink if needed  along the flexitem */
flex-basis: 200px;                /* it sets the initial main size of a flex item */ 
flex: 1 1 200px;                  /* flex-grow: 1, flex-shrink: 1, flex-basis: 200px */
align-self: auto;                /* Default - follows align-items */
align-self: flex-start;
align-self: flex-end;
align-self: center;
align-self: baseline;
align-self: stretch;

align-self an item along the cross axis

it is high priority alignself > align item



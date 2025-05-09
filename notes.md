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


align-items: stretch;             /* Default - stretch to fill the container */
align-items: flex-start;          /* Align to start */
align-items: flex-end;            /* Align to end */
align-items: center;              /* Align to center */
align-items: baseline;            /* Align by text baseline */


align-content: stretch;           /* Default - stretches items */
align-content: flex-start;
align-content: flex-end;
align-content: center;
align-content: space-between;
align-content: space-around;



Properties of Flex Items:

flex-grow: 1;                     /* Item can grow to fill space */
flex-shrink: 1;                   /* Item can shrink if needed */
flex-basis: 200px;                /* Sets initial width/height of the item */
flex: 1 1 200px;                  /* flex-grow: 1, flex-shrink: 1, flex-basis: 200px */
align-self: auto;                /* Default - follows align-items */
align-self: flex-start;
align-self: flex-end;
align-self: center;
align-self: baseline;
align-self: stretch;



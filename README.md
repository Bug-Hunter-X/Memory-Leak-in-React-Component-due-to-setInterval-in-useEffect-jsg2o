# React useEffect setInterval Cleanup
This example demonstrates a common mistake in React: using setInterval within the useEffect hook without proper cleanup. This leads to memory leaks because the interval continues to run even after the component unmounts.

The `bug.js` file contains the problematic code. The `bugSolution.js` file provides a corrected version with cleanup.
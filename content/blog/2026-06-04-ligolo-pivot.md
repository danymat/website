+++
title = "Perform multiple pivot with ligolo-ng"
description = "How to perform double pivot (or more) with ligolo-ng"
date = 2026-06-04
updated = 2026-06-04
draft = false
+++

With ligolo-ng, it is VERY easy to do multiple pivots. For instructions on how to create a pivot, head over to [ligolo-ng's README](https://github.com/nicocha30/ligolo-ng).

To create multiple pivots like this:

![ligolo](/blog/ligolo-double-pivot.png)

The most important thing to know is: Create one listener for the first session that redirects to the same port of listener ligolo proxy.  
For example, if you created a proxy like:

```bash
./proxy -selfcert -laddr 0.0.0.0:9001
```

Then, the first session should have (the important part is the port in `--to` ):

```bash
listener_add --addr 0.0.0.0:9001 --to 127.0.0.1:9001 --tcp
```

- Other resource: [https://4pfsec.com/ligolo](https://4pfsec.com/ligolo)

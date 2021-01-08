# warpads
**Mimics MCBRAWL.COM war server sponges**


Walk on a sponge and you will jump.

Change player speed: `public double speed = 3.5D;`

Gets adjacient sponge blocks:
`        Block b1 = checkBlock(b, Material.SPONGE, 1, -1, 0);
        Block b2 = checkBlock(b, Material.SPONGE, -1, -1, 0);
        Block b3 = checkBlock(b, Material.SPONGE, 0, -1, 1);
        Block b4 = checkBlock(b, Material.SPONGE, 0, -1, -1);`

Up to 4 sponge blocks can be used.

# Rigbench: Build-a-PC (example demo)

**[▶ Try the live demo](https://sairajpulaparthi1.github.io/rigbench-demo/)**

> **Example demo.** Rigbench is a made-up computer store. Every product, part name and price is invented sample data, and nothing here is connected to a real company.

## The idea

Custom PCs fail in two places: the customer picks parts that don't work together, and the store sells a model it can't actually build from what's on the shelf. Rigbench puts both sides on the same stock.

- **Build your PC (customer):** pick a processor, motherboard, memory, graphics, storage, cooler, power supply and case. Every option that won't work is marked with the reason ("Wrong socket", "Too long for the case", "Can't cool it"), and the summary explains each check in plain English, shows a power budget with headroom, the total price, and whether it ships now or is held up by an out-of-stock part. Start from any ready-to-ship model and customize it.
- **Ready-to-ship (store):** five models, each showing **how many can be assembled right now** and the part holding it back. Out of low-profile coolers? The Mini X7 drops to zero. **Assemble 1** deducts the parts.
- **Parts stock:** every part with its count, a bar against its target level and an In stock / Low / Out status. Update with − / +, type a number, or tap **+ Delivery** to add a supplier pack.
- **Reorder:** everything under 75% of its target, with a suggested order rounded up to whole packs, and **Mark received** when it arrives.

A single HTML file with plain JavaScript. Changes are saved in your browser; **Reset demo** restores the sample data.

---
title: "Blocks and connections"
updated: 2023-08-15
---

All flows are made up of _blocks_ and _connections_. Blocks can create information, make a decision, or perform an action. Blocks work together using connections, which enable multiple blocks to do a task together.

## Contents

* [Blocks](#blocks)
* [Connections](#connections)

### Blocks

All blocks have an input, an output, or both. Inputs are on the left side of a block, and outputs are on the right. The [list of all blocks](/docs/postman-flows/reference/blocks-list/) has an explanation and example for every block in Postman Flows.

There are three ways to add a new block:

* Right-clicking anywhere in the flow.
* Selecting the **+ Block** button on the toolbar.
* Dragging a connection from the output of another block.

Any of these actions will open up the block list which you can select from and that block will be added to the flow.

<img src="https://assets.postman.com/postman-labs-docs/concepts/updated-adding-a-block.gif" alt="Add a block" fetchpriority="low" loading="lazy" />

When you open a new flow, the first block you'll see is the **Start** block.

The **Start** block has a single output. When you select the **Run** button, this block sends information through a connection to the next block, causing it to run.

When you create a new flow, before you add any blocks, the start block has colored suggestions for things you can do:

* Send a request: Creates a send request block.
* Add blocks: Opens the block menu.
* Explorer templates: Opens up a menu of prebuilt flows to load and discover.

These are suggestions to help you get started building a flow.

### Connections

Connections are how blocks interact with each other. Dragging a connection from the output of one block to the input of a another block can either cause the second block to run, or pass information to that block and then run it.

<img src="https://assets.postman.com/postman-labs-docs/concepts/updated-adding-a-connection.gif" alt="Add a connection" fetchpriority="low" loading="lazy" />

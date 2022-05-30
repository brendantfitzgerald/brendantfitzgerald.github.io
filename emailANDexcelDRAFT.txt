# Email and Excel
## Considerations before implementing new software

Your business is growing. You have different roles on different teams performing different jobs with different processes.
(Or you just hired someone from a different company.)
Isn't it time you joined the 21st century and got an AtlasForce365 license?

It'll give Accounts Receivable insight into your sales pipeline! 
IT can forecast on-call schedules based on a combination of factory inventory and employee PTO!
Track every conversation with a search, some scrolling, and a few clicks of a mouse!

It's going to revolutionize how you do things, and of course, revolutions come cheap and smooth.

However, many businesses revolutionize their processes without understanding their current state.
G.K. Chesterton already put "change for change's sake" [better than I ever could.](https://en.wikipedia.org/wiki/G._K._Chesterton#Chesterton's_fence)

##  (Mis)understanding the current state of the process

I don't need to tell you about your business. You're an executive, of course you know how the business works!

But frequently, processes are over-simplified. 
For instance, a step in the production process might be "order parts from supplier". What's missing?
To start:
- Whose job is it to order the parts?
- How do they know when to order parts?
- How do they know what parts to order?
- What information do they need to provide the supplier?
- How do they track the status of an order?

These questions all have answers. But if they're not documented, you don't actually know how AtlasForce365 is going to change the process, or if it even will.
That's going to cause a headache for whoever's responsible for Change Management, because they won't know what changes they need to manage.
(You have a change manager, right?)

## One path toward understanding the process

Most of this misunderstanding of business process comes down to existing technological complexity.
In the previous example, "contacting the supplier" could be a paper order form, a phone call, a web page, or a dedicated app.
Each of which would change how the employee tracks the status of the order.
They may have to scan a paper order form, or print a confirmation screen and file it.

The solution to understanding complex systems is to simplify the **mechanisms**, not the process.

*Simplified, there are only two mechanisms, communication and storage. Email and Excel.*

Describing the process in terms of Email and Excel provides a common language to understand the processes.
It eliminates vendor-specific dependencies and gets right to the meat of what needs to happen at every step.

## Back to ordering parts from the supplier.
In the reality of our fictional example, ordering parts is mostly automated by LegacyTech.exe running on a workstation at the factory office.
But "use LegacyTech.exe to order parts" doesn't tell you much about the process.

What if we limited our mechanisms to Email and Excel?

1. The Production Manager emails the Ordering Specialist with *Make*, *Model*, and *Quantity* of widgets being produced.
2. The Ordering Specialist enters that information into *OrderList.xlsx* (with columns for *Order Number* and *Status*)
3. The Ordering Specialist references *PartsList.xlsx* for the parts needed for the Makes and Models of the widgets.
4. The Ordering Specialist contacts the supplier (via whatever means) and orders the parts.
5. The Ordering Specialist adds the Order Number and Status to OrderList.xlsx and emails the Production Manager with the Status.

"But that's going backwards! The Production Manager just uses LegacyTech.exe!" you cry, seeing yet not understanding.

Now you know the important parts of what LegacyTech.exe is doing. 
Do the same for every process in the business, and you have a baseline of how to run your business with two programs.

When the AtlasForce365 sales process gets started, you can hand them that flow chart and have them pitch their solutions.
Assuming you decide to implement their software, you can manage the changes, because you know what you're changing.

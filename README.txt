AYMA STORE V11 — multi-model orders
Update your existing Netlify project via Deploys.
Choose model/color/size/quantity, click Add to basket, then repeat for another model. Added items can be removed before submitting. Customer details are entered once. If basket is empty, submission uses the current selection.
Each item is stored as a separate row in Commandes, sharing the same order reference prefix with -1, -2 etc. Sum their Total cells for the order total. Delivery remains free. No Apps Script update needed.
Submission is sequential: failed batches keep confirmed progress and lock details; retry completes remaining items with the same IDs. Do not process incomplete orders until confirmed with customer.
Prices: Model 1 119 MAD; Model 2 and 3 139 MAD.

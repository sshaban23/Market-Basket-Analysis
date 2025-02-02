# Market-Basket-Analysis

A1: PROPOSAL OF QUESTION:

What items do customers often buy together, and how can this information help improve store layout and promotions?

A2: DEFINED GOAL:

One of my goals is to identify the top 3 most frequently purchased item combinations in the dataset and recommend changes to the store layout and promotional strategies to increase sales.
 
B1: EXPLANATION OF MARKET BASKET:

Market basket analysis helps us understand which products customers frequently buy together. By analyzing the transactions in our dataset, we can find patterns and associations between items, like discovering that customers who buy printer ink also often purchase printer paper. This information can help us make better decisions about product placement in the store, create effective product bundles for promotions, and enhance our marketing strategies, ultimately leading to more sales and a better shopping experience for our customers.

B2: TRANSACTION EXAMPLE:

A customer purchased "Logitech M510 Wireless Mouse," "HP 63 Ink," "10ft iPhone Charger Cable," "Creative Pebble 2.0 Speakers," and "SanDisk Ultra 128GB card."

B3: MARKET BASKET ASSUMPTION:

One assumption of market basket analysis is that the items in each transaction are associated with one another, meaning that if a customer buys a certain item, they are more likely to buy another specific item. This assumption allows us to explore and quantify relationships between different products, assuming that the presence of one item can influence the likelihood of purchasing another, rather than viewing each item purchase as an independent event.

![image](https://github.com/user-attachments/assets/07eb34a7-7653-44b4-8592-97a787f24b1e)

C3: ASSOCIATION RULES TABLE:

Rule 1: (10ft iPhone Charger Cable 2 Pack) -> (Dust-Off Compressed Gas 2 pack)
•	Support: 0.023064
•	Confidence: 0.456464
•	Lift: 1.914955

Rule 2: (Dust-Off Compressed Gas 2 pack) -> (10ft iPhone Charger Cable 2 Pack)
•	Support: 0.023064
•	Confidence: 0.096756
•	Lift: 1.914955

Rule 3: (Anker USB C to HDMI Adapter) -> (Dust-Off Compressed Gas 2 pack)
•	Support: 0.024397
•	Confidence: 0.356725
•	Lift: 1.496530

Rule 4: (Dust-Off Compressed Gas 2 pack) -> (Anker USB C to HDMI Adapter)
•	Support: 0.024397
•	Confidence: 0.102349
•	Lift: 1.496530

Rule 5: (Anker USB C to HDMI Adapter) -> (VIVO Dual LCD Monitor Desk mount)
•	Support: 0.020931
•	Confidence: 0.306043
•	Lift: 1.757755

C4: TOP THREE RULES:

Rule 1: This rule indicates that customers who purchase a "10ft iPhone Charger Cable 2 Pack" have a 45.65% chance of also buying "Dust-Off Compressed Gas 2 pack." The lift of 1.91 suggests that these items are almost twice as likely to be bought together compared to being bought independently.

Rule 2: This rule shows that customers who buy "FEIYOLD Blue light Blocking Glasses" also purchase "Dust-Off Compressed Gas 2 pack" 41.90% of the time. The lift value of 1.76 indicates a significant positive association, meaning that the purchase of the glasses increases the likelihood of also buying the compressed gas pack.

Rule 3: This rule reveals that when customers purchase a "SanDisk Ultra 64GB card," there is a 41.66% probability they will also buy a "Dust-Off Compressed Gas 2 pack." The lift of 1.75 suggests a strong association between these items, indicating they are frequently purchased together.

![image](https://github.com/user-attachments/assets/d9527731-bc80-4e45-a961-7101a9d66aa9)

D1: SIGNIFICANCE OF SUPPORT, LIFT, AND CONFIDENCE SUMMARY:

The analysis showed that products like the "10ft iPhone Charger Cable 2 Pack" and "Dust-Off Compressed Gas 2 pack" are frequently bought together, with a support of 0.023064, confidence of 0.456464, and a lift of 1.914955. Also, "FEIYOLD Blue light Blocking Glasses" and the "Dust-Off Compressed Gas 2 pack" showed a strong association with a confidence of 0.419028 and lift of 1.757904. I also saw that, the combination of "SanDisk Ultra 64GB card" with the "Dust-Off Compressed Gas 2 pack" had a support of 0.040928 and a confidence of 0.416554. These results show that these items are often purchased together, suggesting great opportunities for cross-selling and product bundling. This information is valuable for optimizing store layouts, crafting promotions, and enhancing overall sales strategies.

D2: PRACTICAL SIGNIFICANCE OF FINDINGS:

The practical significance of these findings is that we can use the insights to boost our sales and improve the shopping experience. By knowing which products, like charger cables and compressed gas packs, are frequently bought together, we can place these items near each other in the store or online, making it easier for customers to find and purchase them. Also, we can create special promotions or bundles for these popular item combinations, encouraging customers to buy more. This will increase our sales and also enhances customer satisfaction by providing a more convenient and appealing shopping experience.

D3: COURSE OF ACTION:

I recommend that we rearrange our store layout and online shopping categories to place frequently bought-together items, like charger cables and compressed gas packs, closer to each other. We should also create special bundle deals or discounts for these combinations to encourage customers to buy them together. Also, promoting these bundles in our marketing campaigns can attract more customers and increase sales. By taking these actions, we can make it easier for customers to find related products, improve their shopping experience, and boost our overall sales.
 























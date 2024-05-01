# Big-Data-Project-Analysis-on-Swiggy-Zomato-Order-Information-Dataseton
This is a project including different Big Data Analytics on a popular dataset called Swiggy/Zomato Order Information on the internet. This analysis include different detailed representations and visual representations on the dataset.

Rows of the dataset:-

order_id : unique id for each order
order_time: time of the creation of order by the client
order_date : date of the order
allot_time: time of allocation of order to the rider
accept_time: time of acceptance of the order by the rider (if available)
pickup_time: time of pickup of the order (if available)
delivered_time: time of delivery of the order (if available)
cancelled_time: time of cancellation of order (if the order was cancelled)
cancelled: whether the order was cancelled
rider_id: unique id for each rider
first_miledistance: road distance fromdistance: road distance from rider’s location to the pickup location
last_miledistance: road distance from pickup location to the delivery location
allotted_orders: total number of orders allotted to the rider in the 30 days before (not including) orderdate
delivered_orders: total number of orders delivered by the rider in the 30 days before (not including) order_date
-date
undelivered_orders: total number of orders allotted to but not delivered by the rider (i.e. cancelled) in the 30 days before (not including) orderdate
lifetime_ordercount: total number of orders delivered by the rider at any time before orderdate
reassigned_order: whether the order was reassigned to this rider
reassignment_method: if the order was reassigned, whether the reassignment was done manually (by the ops team) or automatically
reassignment_reason: a more detailed reason for the reassignment
session_time: total time the rider had been online on orderdate before ordertime

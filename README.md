# NodeRed-FailRetry
One of my Node-Red subflows for Google Summer of Code. (Asynchronous Request-Reply pattern implemented...)

DESCRIPTION: This flow allows the user to check the nodes or operations for failures and then retry for chosen amount of times. The user can choose the key to check for and also choose if flow should check for failures or a success. Once a message comes without a failure indicator(or with a success indicator) within retries the message is passed to another node or operation. If such case can not be reached the flow returns an error and the message can not be passed to other operations. With these specifications, this flow can be used to create Back-End To-Do Lists. These To-Do Lists will not be occupied by the messages that have failed at the very first steps. And also the user will be able to see if some of their operations have some problems to fix and which one.

(FOR A DETAILED DESCRIPTION PLEASE VISIT MY NODE-RED PAGE)

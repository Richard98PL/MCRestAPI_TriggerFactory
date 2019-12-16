# triggerFactoryAndRestAPI
triggerFactoryAndRestAPI

Trigger Factory Pattern on Order Object, using REST API to send OrderItems to Marketing Cloud

1. sk_TriggerFactory.createHandler(Order.SObjectType) on sk_OrderTrigger
2. createHandler using getHandler() method
3. getHandler returning object of class sk_OrderTriggerHandler
4. calling execute() method from sk_TriggerFactory on above object
5. calling a proper method from this above object which implements sk_ITrigger

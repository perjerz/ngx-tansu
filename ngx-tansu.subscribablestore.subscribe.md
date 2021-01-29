<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [ngx-tansu](./ngx-tansu.md) &gt; [SubscribableStore](./ngx-tansu.subscribablestore.md) &gt; [subscribe](./ngx-tansu.subscribablestore.subscribe.md)

## SubscribableStore.subscribe() method

A method that makes it possible to register "interest" in store value changes over time. It is called each and every time the store's value changes. A registered subscriber is notified synchronously with the latest store value.

<b>Signature:</b>

```typescript
subscribe(subscriber: Subscriber<T>): Unsubscriber;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  subscriber | [Subscriber](./ngx-tansu.subscriber.md)<!-- -->&lt;T&gt; | a subscriber in a form of a [SubscriberFunction](./ngx-tansu.subscriberfunction.md) or a [SubscriberObject](./ngx-tansu.subscriberobject.md)<!-- -->. Returns a [Unsubscriber](./ngx-tansu.unsubscriber.md) (function or object with the <code>unsubscribe</code> method) that can be used to unregister and stop receiving notifications of store value changes. |

<b>Returns:</b>

[Unsubscriber](./ngx-tansu.unsubscriber.md)

The [UnsubscribeFunction](./ngx-tansu.unsubscribefunction.md) or [UnsubscribeObject](./ngx-tansu.unsubscribeobject.md) that can be used to unsubscribe (stop state change notifications).

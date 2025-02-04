<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [QueueEvents](./bullmq.queueevents.md) &gt; [on](./bullmq.queueevents.on.md)

## QueueEvents.on() method

Listen to 'active' event.

This event is triggered when a job enters the 'active' state.

<b>Signature:</b>

```typescript
on(event: 'active', listener: (args: {
        jobId: string;
        prev?: string;
    }, id: string) => void): this;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  event | 'active' |  listener |
|  listener | (args: { jobId: string; prev?: string; }, id: string) =&gt; void |  |

<b>Returns:</b>

this


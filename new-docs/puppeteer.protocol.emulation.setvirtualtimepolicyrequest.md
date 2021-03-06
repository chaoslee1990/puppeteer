<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Emulation](./puppeteer.protocol.emulation.md) &gt; [SetVirtualTimePolicyRequest](./puppeteer.protocol.emulation.setvirtualtimepolicyrequest.md)

## Protocol.Emulation.SetVirtualTimePolicyRequest interface

<b>Signature:</b>

```typescript
export interface SetVirtualTimePolicyRequest 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [budget](./puppeteer.protocol.emulation.setvirtualtimepolicyrequest.budget.md) | number | If set, after this many virtual milliseconds have elapsed virtual time will be paused and a virtualTimeBudgetExpired event is sent. |
|  [initialVirtualTime](./puppeteer.protocol.emulation.setvirtualtimepolicyrequest.initialvirtualtime.md) | [Network.TimeSinceEpoch](./puppeteer.protocol.network.timesinceepoch.md) | If set, base::Time::Now will be overriden to initially return this value. |
|  [maxVirtualTimeTaskStarvationCount](./puppeteer.protocol.emulation.setvirtualtimepolicyrequest.maxvirtualtimetaskstarvationcount.md) | [integer](./puppeteer.protocol.integer.md) | If set this specifies the maximum number of tasks that can be run before virtual is forced forwards to prevent deadlock. |
|  [policy](./puppeteer.protocol.emulation.setvirtualtimepolicyrequest.policy.md) | [VirtualTimePolicy](./puppeteer.protocol.emulation.virtualtimepolicy.md) |  |
|  [waitForNavigation](./puppeteer.protocol.emulation.setvirtualtimepolicyrequest.waitfornavigation.md) | boolean | If set the virtual time policy change should be deferred until any frame starts navigating. Note any previous deferred policy change is superseded. |


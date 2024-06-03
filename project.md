# 16-bit CPU

Let's start with a 

* ALU;
* Controller;
* Pipeline;
* MMU;
* Caches;
* Prefetching;
* Out-of-order execution;
* Superscaler;
* Branch prediction;

---

Why wouldn't we start our journey by designing our own 16-bit CPU? Well, even though you might have a reason why not to, I'm still doing it!

This exercise wants to be one educational: what are the different component of CPU and how do they work together? The `registers`, the `ALU`, the `controller`, all of which can be further optimize to do the same things faster. We will not only explain how a `pipeline` works, we will do it! In my opinion, there are no better way to really understand how something works. And depending on how much time we have and need, we can go deeper and implement `prefetching`, `superscalar` and `out-of-order` execution, attach `L1 Cache` and implement simple `branch prediction` functionnality. And who knows, what not going all-in and make it a dual-core!!!

But a CPU is nothing without software. So we will create our own `assembly` language and tooling to make sure our CPU is not idling forever. The booting process (`bootstraping`), along with our `assembly calling convention` will be needed if we want to run something useful.
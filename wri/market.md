# Thu Nov  2 15:11:58 EDT 2017

polina [2:56 PM] 
you know what could be an interesting part for aorta to eventually explore?


[2:56] 
i18n.


jeff [3:03 PM] 
Agreed.  I had been thinking of UI pipelines; once APIs have been normalized — harder than it sounds, but that’s my core value prop —  it should be straight-forward to support  design patterns like Decorator, Composite, and Chain of Command.  The sample I had suggested to Mark W. was to insert Google Translate automatically into a voice/textual interface.


[3:08] 
Implementing real, high-quality i18n as a pipeline stage is probably a gargantuan effort in its own right.  It might be a good example of something a third-party could build on top AORTA.  As an example, consider Heth:

1. Heth is an end-user application.
2. AORTA is the platform on which Heth is built.
  - AORTA provides consistent API for chat-like UIs.
3. A third-party company offers AORTA a pipeline stage for i18n.
  - The i18n stage may require manual translation by a consultancy;
  - or, it may be a completely automated, COTS drop-in;
  - but most likely, it’s somewhere in the middle. (edited)


[3:11] 
In fact, there really ought to be a marketplace for component libraries build atop AORTA.  The more and better stages are available, the greater the value of AORTA to applications like Heth.


polina [3:12 PM] 
platformization is all the rage these days


jeff [3:14 PM] 
Heh, has been for some time now.  It’s kind of like AI, or God, in that it’s popular mostly because it’s so ill-defined.  When people declare their companies to be “platforms,” they usually mean they want recurring revenue for a sticky (i.e., hard to ditch) product.

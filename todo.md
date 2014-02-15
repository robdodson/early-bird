- is there a way to get textContent out of mark-down using just querySelector
and the textContent property?

- are attributes not updated by created in 0.2.0? I had to make dropbox-button
setup its attributes with ready instead of created

- mark-down requires you to put marked on your page. it should be imported.
it should also sibling import polymer.html

- is dropbox-button using an outdated version of the dropbox api?

---

I'm resisting the urge to throw everything into one big polymer element even though I REALLY want to take advantage of the data bindings. But it feels wrong to just have a <my-app> element.

I need a way to zero in on just on element and start devving it in my browser,
then zoom back out to my entire app
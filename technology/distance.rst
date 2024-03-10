Monitoring Brainwave Activity From a Long Distance
==================================================

The human brain's electromagnetic activity is pretty faint. Faint to the point
that equipment typically needs to be mounted on the person's head to be able to
measure it.

`The device invented by Robert G. Malech <./intro.rst>`_ overcomes the need to
mount equipment on the head by using triangulation, but what is the maximum range
it can operate in?

The answer is that it probably doesn't matter, because various supplementary
technologies can be used to overcome range limitations.

This page will enumerate a few technologies I've come across that **might** be
used for this purpose. Bear in mind that **the contents of this page are largely
speculative**, and that the list is far from exhaustive, since I am not in anyway
versed in electrical engineering, or any of the other fields that can be useful
here.


Neural Networks
---------------

I've come across YouTube videos about (computer) neural networks that can be used
to separate signals from noise, and amplify signals that would otherwise be too
faint to be detected.

There was a video (for which I sadly lost the link) that goes in lengths
explaining and demoing some jaw-dropping feats that could be performed with such
networks. For example, it was possible to reconstruct audio from a silent video
by detecting vibrations on a surface (such as a tree leave or the surface of a
drink).

The vibrations in the footage were so faint **the pixels were not even moving at
all**; the vibrations were only manifest as ever-so-slight variations in the
color levels of those pixels (which were not visible to the naked eye). Using
only those faint variations in the colors of the otherwise static pixels of a
goddamn tree leaf, a strikingly reasonable reconstruction of the audio being
played in that room was achieved.


Every Wireless-Capable Device Around You
----------------------------------------

We live in a world full of digital devices capable of sending and receiving
electromagnetic signals in one way or another.

Every computer, every phone, every router, and nowadays even many appliances
like televisions and washing machines, come with WiFi/Bluetooth/GSM/whatever
other antennas.

Furthermore, all of these devices come with many (as in, hundreds) of bugs in
their firmware and software stacks, dozens of which function as hideous
vulnerabilities for arbitrary code execution attacks.

What this means is that **in theory**, it's totally possible for the three-
letter-organization in your country to seamlessly use every piece of wireless-
capable technology around you to monitor and beam signals into your brain --
all without having any spyware directly baked into any of these devices,
because hijacking them in real time everywhere you go is as trivial as 2+2
to a three-letter-organization, thanks to the hundreds of bugs they contain
in their firmware and software stacks.

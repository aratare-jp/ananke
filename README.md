# `ananke`

```
The personification of inevitability, compulsion and necessity.
```

A Clojure/Script library designed to tame applications so you don't have to scream at night anymore.

# Status
Ultra alpha, so it's for those who want to live beyond the edge.

# Rationale
As you start creating a new application, you feel joy and happiness. But as time goes by and the application grows more complex, your hair starts falling and you feel less joy and happiness. Eventually, you're bald and your application is a complete mess. And I'm sure the latter is much worse.

One of the most headache-inducing complexities in an application is application state. Specifically, things that you want to do at a certain state. Take a login form for example, you want to validate when the user stops typing, to validate on submitting requests, to error out on failed request, to clear the form when the user hits "Clear", etc. etc. That's a lot of "wants".

And then you realise that this is _only_ just the state. You completely forgot about the transitions between them... It's OK to cry now.

Most of the time, it all boils down to you having different states, and you want to be able to do things when a certain state is reached, and to move to different states depending on different factors. Simply put, you want a `UI State Machine` (USM).

The reason above is why `Ananke` was born. It was born out of `inevitability, compulsion and necessity` of taming your app state in a reliable and predictable way with USMs.

# Installation
TBC

# Documentation
TBC

# License

Copyright © 2021 Rex Truong

This program and the accompanying materials are made available under the
terms of the Eclipse Public License 2.0 which is available at
http://www.eclipse.org/legal/epl-2.0.

This Source Code may also be made available under the following Secondary
Licenses when the conditions for such availability set forth in the Eclipse
Public License, v. 2.0 are satisfied: GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or (at your
option) any later version, with the GNU Classpath Exception which is available
at https://www.gnu.org/software/classpath/license.html.

![Deliveroo_Logo svg](https://github.com/user-attachments/assets/b5abd3cc-29e6-4daa-96c7-3bb78e5440b1)

December 2023 - Present

> [!NOTE]
> This is probably just 60% of my work. A lot of things can't be revealed outside + didn't mentioned low impact work which also has big quantity. 

### Summary 

- I am the engineer who focused on _Getting things done_ and helped the organisation move faster with good-quality work.
- I started as an Android engineer, but eventually had to do full-stack ( Android + iOS + React + Ruby + Golang + AWS ) as we are a small team but with a lot of product work.

 Weird flex alert

I'm the only person in the organisation who made decent contributions to all five public-facing apps—restaurant ( Android), rider, and consumer ( Android + iOS ) — at the organisation's current state. 


### Features delivered 

> For feature delivery, how I did matters more than what I did

- Export receipt generation logic from on-device to backend for faster iteration on changes ( golang + Restaurant Android )

- Self-serve cancellation feature in restaurants ( Restaurant Android )
- Ability to substitute items after the order is placed (Restaurant Android + Consumer iOS + Consumer Android )

Read more about the experience here [here](https://help.deliveroo.com/en/articles/10156329-item-substitutions) 

- Ability for riders to scan the receipts using OCR to cut down the number of wrong orders ( Rider iOS )

Read more about the experience [here](https://riders.deliveroo.co.uk/en/support/orders/how-do-i-scan-the-order-receipt) 

- Launched bundles to the consumers globally ( Involved a lot of basket and add to cart calculations with existing offers )


## No one asked me to do

#### Stability work 

<img width="683" alt="Screenshot 2025-04-28 at 9 59 31 PM" src="https://github.com/user-attachments/assets/3a823069-6626-4f0f-ba27-f3a4680455df" />

- Improved crash-free sessions metrics of restaurants by ~3%, leading to 99.98%
- My work on baseline profiles which decreased ~30% of the app startup time got highlighted in company annual Android-onsite event to all the other apps 

#### Against to rewriting

When I joined the restaurant team, everyone was discussing how they wanted to do a full rewrite of the app, as the current app is very old and not scalable, and there's a proposal to leadership as well.

I'm not a fan of rewrites. I took a bet and, in my free time ( after delivering features actively ), I worked on doing the safe refactoring of the app.

These are things which I did 

- Introduce Jetpack Compose to the codebase with the org's design system support, which not only supported the refactoring but also improved developer productivity
- A lot of Android Lint checks to avoid mistakes made previously
- Migrated the codebase to Dagger Hilt, which cut down ~50% of boilerplate code in the codebase
- Introduced coroutine support and deprecated the RxJava foundation
- Deprecated a lot of the Base* class and wrote its composition alternatives

All these wouldn't be possible without the help of two other amazing engineers in the team who believed and supported my decisions. 

#### Enable Ai reviews

- Did the platform work required to enable the Ai codereviews for all the repositories in the org. It will be first one to review your work saving humans time for small mistakes on the PRs

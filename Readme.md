# Digital card management app

## Overview

We’re building an app called “CardMaster”, which will allow users to manage all cards in one place.

The users can easily manage their balance between cards and transfer funds across in a single page.

The app lets users manage credit and debit cards with ease, and allows e.g. negative credits being paid off, or increase an already large balance.

The app allows the user to add multiple cards to their collection (max 5 cards).

- The app will show them their credit and debit cards with the card number hidden, except the last 4 digits, but if they want to see all details, they can enter a 4 digit secret code to reveal.
- Besides viewing the cards, they can also transfer money across cards, but it can never go below 0 for debit cards. For credit cards, the balance can be below 0, up to a max credit limit.
- When transferring money across to cards, credit cards have a transaction fee of a certain percentage. When the user transfers money out of the card, a certain percentage of that money will be “lost” to transfer-fees.

## Task

Using react and TS, build an app that lets users manage their debit and credit cards in a single page.

The app will have a “Dashboard” to manage their cards and a page where the transaction history is kept, which shows transfers and transaction fees (if applicable).

## Assumptions

Any transfer has to be from a card to another card

Any card can transfer to any other card

Example credit cards:

- AMEX Platinum - Credit limit 10,000 - no transfer fee
- AMEX Gold - Credit limit 5,000 - 0.19% transfer fee
- VISA - Credit limit 1,000 - 2.9% transfer fee
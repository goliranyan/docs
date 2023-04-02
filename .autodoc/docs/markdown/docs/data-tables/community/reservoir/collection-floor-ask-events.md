[View code on GitHub](https://dune.com/docs/data-tables/community/reservoir/collection-floor-ask-events.md)

# Collection Floor Ask Events

This section of the app technical guide covers the `reservoir.collection_floor_ask_events` table, which contains records with information about each collection floor ask change. The table includes columns such as `id`, `kind`, `collection_id`, `contract`, `token_id`, `order_id`, `maker`, `price`, `previous_price`, `valid_until`, `source`, `tx_hash`, `tx_timestamp`, and `created_at`.

The `id` column is an internal event ID, while the `kind` column specifies the type of event (e.g. new-order, expiry, sale, cancel, balance-change, approval-change, bootstrap, revalidation, reprice). The `collection_id` column contains the ID of the collection, and the `contract` column contains the contract address. The `token_id` column specifies the ID of the token in the collection, and the `order_id` column contains the associated ask ID. The `maker` column contains the wallet address of the associated ask maker, and the `price` column contains the associated ask price in native currency. The `previous_price` column contains the previous floor ask price in native currency, and the `valid_until` column specifies the expiration of the associated ask. The `source` column contains the source of the order (e.g. opensea.io), while the `tx_hash` column contains the associated transaction hash. The `tx_timestamp` column specifies the timestamp of the associated transaction, and the `created_at` column contains the timestamp the event was recorded.

This section also includes query examples for the `reservoir.collection_floor_ask_events` table, which can be found at the following links:

- [https://dune.com/queries/1302799/2232083](https://dune.com/queries/1302799/2232083)
- [https://dune.com/queries/1302841/2232151](https://dune.com/queries/1302841/2232151)

Overall, this section of the app technical guide provides a detailed overview of the `reservoir.collection_floor_ask_events` table and its columns, as well as query examples for working with the table.
## Questions: 
 1. What is the purpose of the `reservoir.collection_floor_ask_events` table in the context of the Dune Docs project? 
   - The `reservoir.collection_floor_ask_events` table contains records with information about each collection floor ask change.
2. What kind of events are included in the `kind` column of the table? 
   - The `kind` column includes event types such as new-order, expiry, sale, cancel, balance-change, approval-change, bootstrap, revalidation, and reprice.
3. Are there any limitations or restrictions on the data that can be queried from this table? 
   - The app technical guide does not provide information on any limitations or restrictions on the data that can be queried from this table.
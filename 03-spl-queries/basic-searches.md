# Lab 02: Basic SPL Searches

## Objective

Learn to search and retrieve security events using Splunk Search Processing Language (SPL).

## Query 1: Display All Events

```spl
index=YOUR_INDEX
```

**Explanation:** Retrieves events from the specified index.

Replace `YOUR_INDEX` with the actual index containing your logs.

## Query 2: Display Selected Fields

```spl
index=YOUR_INDEX
| table _time, user, src_ip, dest_ip, event_id, severity
```

**Explanation:** Displays selected fields in a table for easier investigation.

## Learning Outcome

Understanding basic event searches and field selection in Splunk.

## Evidence

Screenshots and verified results will be added after executing these queries.

# Changelog

## 1.6.0
  * Adds support for bookmarking within an attribution window to prevent a hung sync [#36](https://github.com/singer-io/tap-adwords/pull/36)

## 1.5.0
  * Adds the Call Metrics Call Details, Display Keyword Performance, Display Topics Performance, Account Performance, and Video Performance Reports [#34](https://github.com/singer-io/tap-adwords/pull/34)

## 1.4.0
  * Adds the "Shopping Performance Report" to the list of available reports [#25](https://github.com/singer-io/tap-adwords/pull/25)

## 1.3.3
  * Allows the downloading of Reports to happen as a stream to improve memory consumption [#28](https://github.com/singer-io/tap-adwords/pull/28)

## 1.3.2
  * Adds the Keywordless Query Report [#27](https://github.com/singer-io/tap-adwords/pull/27)

## 1.3.1
  * Reverts a change to set the default page size of Adwords responses back to 1000 [#26](https://github.com/singer-io/tap-adwords/pull/26)

## 1.3.0
  * Fixes a bug in selector based code
  * Upgrades the Adwords API version used from v201708 to v201802 [#21](https://github.com/singer-io/tap-adwords/pull/21)

## 1.2.1
  * Refactors code to be more selector focused and removes some duplication [#23](https://github.com/singer-io/tap-adwords/pull/23)

## 1.2.0
  * Adds support for loading Ads using an ad_group_id when using a CampaignId does not fit into the 100k partition [#22](https://github.com/singer-io/tap-adwords/pull/22)

## 1.1.0
  * Improves the algoirthm to use a binary search to find the correct partition size [#19](https://github.com/singer-io/tap-adwords/pull/19)

## 1.0.23
  * Adjusts the CAMPAIGN_PARTITION_SIZE smaller to handle larger campaigns [#18](https://github.com/singer-io/tap-adwords/pull/18)

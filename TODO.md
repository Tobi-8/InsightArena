- [ ] Add cache-manager injection to MarketsService (CACHE_MANAGER -> cacheManager)
- [ ] In MarketsService.resolveMarket: after DB save, invalidate in-memory trendingCache and external cache keys (trendingEvents + popularEventDetail)
- [ ] In MarketsService.cancelMarket: after DB save, invalidate in-memory trendingCache and external cache keys (trendingEvents + popularEventDetail)
- [ ] Update MarketsService unit tests to mock CACHE_MANAGER and assert del() calls
- [ ] Run backend unit tests


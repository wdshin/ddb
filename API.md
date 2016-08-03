
### Last Write Wins

* ddb:set({B,K},V).
* ddb:get({B,K}).
* ddb:get_in({B,KList}).
* ddb:list_all(B). 
* ddb:for_each(B,Fun).

* ddb:set_values({B,K},Props).
* ddb:get_values({B,K},Fields).
* ddb:get_in({B,KList},Fields).
* ddb:list_all(B,Fields). 
* ddb:for_each(B,Fun).

* ddb:add_to_set({B,K},V)
* ddb:add_to_set({B,K},V,FunOrderBy)
* ddb:get_set({B,K})
* ddb:get_set({B,K},FunOrderBy).
 
* ddb:add_to_list({B,K},V)
* ddb:add_to_list({B,K},V,FunOrderBy)
* ddb:get_list({B,K})
* ddb:get_list({B,K},FunOrderBy).

* ddb:add_to_map({B,K},V)
* ddb:get_map({B,K})

### Atomic Operations

* ddb:atomic_set({B,K},V,Actor).
* ddb:atomic_set_if({B,K},V,If,Actor).
* ddb:atomic_set_if_get({B,K},V,If,Actor).
* ddb:atomic_set_get({B,K},V,Actor).
* ddb:atomic_get({B,K}).

* ddb:atomic_add_to_set({B,K},V,Actor)
* ddb:atomic_add_to_set({B,K},V,FunOrderBy,Actor)
* ddb:atomic_get_set({B,K})
* ddb:atomic_get_set({B,K},FunOrderBy).

* ddb:add_count({B,K},V,Actor).
* ddb:add_count_get({B,K},V,Actor).
* ddb:get_count({B,K}).
* ddb:get_counts_in({B,KList}.

### Transactional Batch Writing Operations

* ddb:begin_transaction(TR,Actor).
* ddb:add_to_transaction(TR,Op).
* ddb:end_tranction(TR,Actor).



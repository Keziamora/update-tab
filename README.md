# update-tab
update table
UPDATE a_lte_mrbts_lnbts_lncel_lncel_fdd a,4g_list_mocn_ns b
SET
a.siteId = b.siteid_after
WHERE
a.mrbtsId = b.mrbtsid and a.lnBtsId = b.lnbtsid AND a.lnCelId = b.lncelid ;


UPDATE a_lte_mrbts_lnbts_lncel_lncel_fdd a,4g_list_mocn_ns b
SET
a.siteId = b.siteid
WHERE
a.mrbtsId = b.mrbtsid and a.lnBtsId = b.lnbtsid AND a.lnCelId = b.lncelid  and a.siteid is NULL ;

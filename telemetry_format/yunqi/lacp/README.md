# LACP

LACP telemetry structure.

<pre>
{
    "protocols": {
        "lacp": {
            "priority": "32768",
            "interface" : [
                {
                    "te-1/1/2": {
                        "priority" : "",
                        "statistics" : {
                            "lacp_rx" : "",
                            "lacp_tx" : "",
                            "marker_rx" : "",
                            "marker_tx" : "",
                            "marker_response_rx" : "",
                            "marker_response_tx" : "",
                            "illegal_rx" : "",
                            "dropped_rx" : "",
                            "unknown_rx" : ""
                        },
                        "local_info" : {
                            "system_priority" : "",
                            "system_id" : "",
                            "port" : "",
                            "port_priority" : "",
                            "admin_key" : "",
                            "oper_key" : "",
                            "admin_state" : "",
                            "oper_state" : "",
                            "selected_agg_id" : "",
                            "attached_agg_id" : "",
                            "aggregate_or_individual" :""
                        },
                        "partner_info" : {
                            "admin_system_priority" : "",
                            "oper_system_priority" : "",
                            "admin_system_id" : "",
                            "oper_system_id" : "",
                            "admin_port" : "",
                            "oper_port" : "",
                            "admin_port_priority" : "",
                            "oper_port_priority" : "",
                            "admin_key" : "",
                            "oper_key" : "",
                            "admin_state" : "",
                            "oper_state" : ""
                        }
                    }
                }
            ],
            "aggregation" : [
                {
                    "ae1" : {
                        "mac_address" : "",
                        "system_priority" : "",
                        "system_id" :"",
                        "aggregate_or_individual" : "",
                        "admin_key" : "",
                        "oper_key" : "",
                        "partner_system_id" : "",
                        "partner_system_priority" : "",
                        "partner_oper_key" : "",
                        "collector_max_delay" : "",
                        "port_list" : [
                            "qe-1/1/49",
                            "qe-1/1/50",
                            "qe-1/1/51",
                            "qe-1/1/52",
                            "qe-1/1/53",
                            "qe-1/1/54"
                        ]
                    }
                }
            ]
        }
    }
}
</pre>

{
    "abi": [
        {
            "inputs": [
                {
                    "name": "amount",
                    "type": "felt"
                }
            ],
            "name": "increase_balance",
            "outputs": [],
            "type": "function"
        },
        {
            "inputs": [],
            "name": "get_balance",
            "outputs": [
                {
                    "name": "res",
                    "type": "felt"
                }
            ],
            "stateMutability": "view",
            "type": "function"
        },
        {
            "inputs": [],
            "name": "constructor",
            "outputs": [],
            "type": "constructor"
        }
    ],
    "entry_points_by_type": {
        "CONSTRUCTOR": [
            {
                "offset": "0x7a",
                "selector": "0x28ffe4ff0f226a9107253e17a904099aa4f63a02a5621de0576e5aa71bc5194"
            }
        ],
        "EXTERNAL": [
            {
                "offset": "0x42",
                "selector": "0x362398bec32bc0ebb411203221a35a0301193a96f317ebe5e40be9f60d15320"
            },
            {
                "offset": "0x63",
                "selector": "0x39e11d48192e4333233c7eb19d10ad67c362bb28580c604d67884c85da39695"
            }
        ],
        "L1_HANDLER": []
    },
    "program": {
        "attributes": [
            {
                "accessible_scopes": [
                    "__main__",
                    "__main__",
                    "__main__.increase_balance"
                ],
                "end_pc": 54,
                "flow_tracking_data": {
                    "ap_tracking": {
                        "group": 6,
                        "offset": 0
                    },
                    "reference_ids": {
                        "__main__.increase_balance.amount": 37,
                        "__main__.increase_balance.pedersen_ptr": 39,
                        "__main__.increase_balance.range_check_ptr": 40,
                        "__main__.increase_balance.syscall_ptr": 38
                    }
                },
                "name": "error_message",
                "start_pc": 50,
                "value": "Amount must be positive. Got: {amount}."
            }
        ],
        "builtins": [
            "pedersen",
            "range_check"
        ],
        "compiler_version": "0.10.1",
        "data": [
            "0x400380007ffc7ffd",
            "0x482680017ffc8000",
            "0x1",
            "0x208b7fff7fff7ffe",
            "0x480680017fff8000",
            "0x53746f7261676552656164",
            "0x400280007ffc7fff",
            "0x400380017ffc7ffd",
            "0x482680017ffc8000",
            "0x3",
            "0x480280027ffc8000",
            "0x208b7fff7fff7ffe",
            "0x480680017fff8000",
            "0x53746f726167655772697465",
            "0x400280007ffb7fff",
            "0x400380017ffb7ffc",
            "0x400380027ffb7ffd",
            "0x482680017ffb8000",
            "0x3",
            "0x208b7fff7fff7ffe",
            "0x480a7ffc7fff8000",
            "0x480a7ffd7fff8000",
            "0x480680017fff8000",
            "0x206f38f7e4f15e87567361213c28f235cccdaa1d7fd34c9db1dfe9489c6a091",
            "0x208b7fff7fff7ffe",
            "0x480a7ffc7fff8000",
            "0x480a7ffd7fff8000",
            "0x1104800180018000",
            "0x800000000000010fffffffffffffffffffffffffffffffffffffffffffffffa",
            "0x480a7ffb7fff8000",
            "0x48127ffe7fff8000",
            "0x1104800180018000",
            "0x800000000000010ffffffffffffffffffffffffffffffffffffffffffffffe6",
            "0x48127ffe7fff8000",
            "0x48127ff57fff8000",
            "0x48127ff57fff8000",
            "0x48127ffc7fff8000",
            "0x208b7fff7fff7ffe",
            "0x480a7ffb7fff8000",
            "0x480a7ffc7fff8000",
            "0x1104800180018000",
            "0x800000000000010ffffffffffffffffffffffffffffffffffffffffffffffed",
            "0x480a7ffa7fff8000",
            "0x48127ffe7fff8000",
            "0x480a7ffd7fff8000",
            "0x1104800180018000",
            "0x800000000000010ffffffffffffffffffffffffffffffffffffffffffffffe0",
            "0x48127ff67fff8000",
            "0x48127ff67fff8000",
            "0x208b7fff7fff7ffe",
            "0x480a7ffc7fff8000",
            "0x480a7ffd7fff8000",
            "0x1104800180018000",
            "0x800000000000010ffffffffffffffffffffffffffffffffffffffffffffffcd",
            "0x480a7ffa7fff8000",
            "0x480a7ffb7fff8000",
            "0x48127ffd7fff8000",
            "0x1104800180018000",
            "0x800000000000010ffffffffffffffffffffffffffffffffffffffffffffffe1",
            "0x48127ffc7fff8000",
            "0x48127ffc7fff8000",
            "0x48127ffc7fff8000",
            "0x48287ffd7ffc8000",
            "0x1104800180018000",
            "0x800000000000010ffffffffffffffffffffffffffffffffffffffffffffffe8",
            "0x208b7fff7fff7ffe",
            "0x482680017ffd8000",
            "0x1",
            "0x402a7ffd7ffc7fff",
            "0x480280007ffb8000",
            "0x480280017ffb8000",
            "0x480280027ffb8000",
            "0x480280007ffd8000",
            "0x1104800180018000",
            "0x800000000000010ffffffffffffffffffffffffffffffffffffffffffffffea",
            "0x40780017fff7fff",
            "0x1",
            "0x48127ffc7fff8000",
            "0x48127ffc7fff8000",
            "0x48127ffc7fff8000",
            "0x480680017fff8000",
            "0x0",
            "0x48127ffb7fff8000",
            "0x208b7fff7fff7ffe",
            "0x480a7ffb7fff8000",
            "0x480a7ffc7fff8000",
            "0x480a7ffd7fff8000",
            "0x1104800180018000",
            "0x800000000000010ffffffffffffffffffffffffffffffffffffffffffffffc3",
            "0x208b7fff7fff7ffe",
            "0x40780017fff7fff",
            "0x1",
            "0x4003800080007ffc",
            "0x4826800180008000",
            "0x1",
            "0x480a7ffd7fff8000",
            "0x4828800080007ffe",
            "0x480a80007fff8000",
            "0x208b7fff7fff7ffe",
            "0x402b7ffd7ffc7ffd",
            "0x480280007ffb8000",
            "0x480280017ffb8000",
            "0x480280027ffb8000",
            "0x1104800180018000",
            "0x800000000000010ffffffffffffffffffffffffffffffffffffffffffffffee",
            "0x48127ffe7fff8000",
            "0x1104800180018000",
            "0x800000000000010fffffffffffffffffffffffffffffffffffffffffffffff1",
            "0x48127ff47fff8000",
            "0x48127ff47fff8000",
            "0x48127ffb7fff8000",
            "0x48127ffb7fff8000",
            "0x48127ffb7fff8000",
            "0x208b7fff7fff7ffe",
            "0x480a7ffb7fff8000",
            "0x480a7ffc7fff8000",
            "0x480a7ffd7fff8000",
            "0x480680017fff8000",
            "0x0",
            "0x1104800180018000",
            "0x800000000000010ffffffffffffffffffffffffffffffffffffffffffffffb0",
            "0x208b7fff7fff7ffe",
            "0x402b7ffd7ffc7ffd",
            "0x480280007ffb8000",
            "0x480280017ffb8000",
            "0x480280027ffb8000",
            "0x1104800180018000",
            "0x800000000000010fffffffffffffffffffffffffffffffffffffffffffffff5",
            "0x40780017fff7fff",
            "0x1",
            "0x48127ffc7fff8000",
            "0x48127ffc7fff8000",
            "0x48127ffc7fff8000",
            "0x480680017fff8000",
            "0x0",
            "0x48127ffb7fff8000",
            "0x208b7fff7fff7ffe"
        ],
        "debug_info": null,
        "hints": {
            "0": [
                {
                    "accessible_scopes": [
                        "starkware.cairo.common.math",
                        "starkware.cairo.common.math.assert_nn"
                    ],
                    "code": "from starkware.cairo.common.math_utils import assert_integer\nassert_integer(ids.a)\nassert 0 <= ids.a % PRIME < range_check_builtin.bound, f'a = {ids.a} is out of range.'",
                    "flow_tracking_data": {
                        "ap_tracking": {
                            "group": 0,
                            "offset": 0
                        },
                        "reference_ids": {
                            "starkware.cairo.common.math.assert_nn.a": 0,
                            "starkware.cairo.common.math.assert_nn.range_check_ptr": 1
                        }
                    }
                }
            ],
            "8": [
                {
                    "accessible_scopes": [
                        "starkware.starknet.common.syscalls",
                        "starkware.starknet.common.syscalls.storage_read"
                    ],
                    "code": "syscall_handler.storage_read(segments=segments, syscall_ptr=ids.syscall_ptr)",
                    "flow_tracking_data": {
                        "ap_tracking": {
                            "group": 1,
                            "offset": 1
                        },
                        "reference_ids": {
                            "starkware.starknet.common.syscalls.storage_read.__temp0": 6,
                            "starkware.starknet.common.syscalls.storage_read.address": 3,
                            "starkware.starknet.common.syscalls.storage_read.syscall": 5,
                            "starkware.starknet.common.syscalls.storage_read.syscall_ptr": 4
                        }
                    }
                }
            ],
            "17": [
                {
                    "accessible_scopes": [
                        "starkware.starknet.common.syscalls",
                        "starkware.starknet.common.syscalls.storage_write"
                    ],
                    "code": "syscall_handler.storage_write(segments=segments, syscall_ptr=ids.syscall_ptr)",
                    "flow_tracking_data": {
                        "ap_tracking": {
                            "group": 2,
                            "offset": 1
                        },
                        "reference_ids": {
                            "starkware.starknet.common.syscalls.storage_write.__temp1": 12,
                            "starkware.starknet.common.syscalls.storage_write.address": 9,
                            "starkware.starknet.common.syscalls.storage_write.syscall_ptr": 11,
                            "starkware.starknet.common.syscalls.storage_write.value": 10
                        }
                    }
                }
            ],
            "75": [
                {
                    "accessible_scopes": [
                        "__main__",
                        "__main__",
                        "__wrappers__",
                        "__wrappers__.increase_balance"
                    ],
                    "code": "memory[ap] = segments.add()",
                    "flow_tracking_data": {
                        "ap_tracking": {
                            "group": 7,
                            "offset": 57
                        },
                        "reference_ids": {
                            "__wrappers__.increase_balance.__calldata_actual_size": 55,
                            "__wrappers__.increase_balance.__calldata_arg_amount": 53,
                            "__wrappers__.increase_balance.__calldata_ptr": 54,
                            "__wrappers__.increase_balance.__temp2": 56,
                            "__wrappers__.increase_balance.pedersen_ptr": 58,
                            "__wrappers__.increase_balance.range_check_ptr": 59,
                            "__wrappers__.increase_balance.ret_value": 60,
                            "__wrappers__.increase_balance.syscall_ptr": 57
                        }
                    }
                }
            ],
            "90": [
                {
                    "accessible_scopes": [
                        "__main__",
                        "__main__",
                        "__wrappers__",
                        "__wrappers__.get_balance_encode_return"
                    ],
                    "code": "memory[ap] = segments.add()",
                    "flow_tracking_data": {
                        "ap_tracking": {
                            "group": 9,
                            "offset": 0
                        },
                        "reference_ids": {
                            "__wrappers__.get_balance_encode_return.range_check_ptr": 71,
                            "__wrappers__.get_balance_encode_return.ret_value": 70
                        }
                    }
                }
            ],
            "128": [
                {
                    "accessible_scopes": [
                        "__main__",
                        "__main__",
                        "__wrappers__",
                        "__wrappers__.constructor"
                    ],
                    "code": "memory[ap] = segments.add()",
                    "flow_tracking_data": {
                        "ap_tracking": {
                            "group": 12,
                            "offset": 27
                        },
                        "reference_ids": {
                            "__wrappers__.constructor.__calldata_actual_size": 98,
                            "__wrappers__.constructor.__calldata_ptr": 97,
                            "__wrappers__.constructor.pedersen_ptr": 100,
                            "__wrappers__.constructor.range_check_ptr": 101,
                            "__wrappers__.constructor.ret_value": 102,
                            "__wrappers__.constructor.syscall_ptr": 99
                        }
                    }
                }
            ]
        },
        "identifiers": {
            "__main__.HashBuiltin": {
                "destination": "starkware.cairo.common.cairo_builtins.HashBuiltin",
                "type": "alias"
            },
            "__main__.assert_nn": {
                "destination": "starkware.cairo.common.math.assert_nn",
                "type": "alias"
            },
            "__main__.balance": {
                "type": "namespace"
            },
            "__main__.balance.Args": {
                "full_name": "__main__.balance.Args",
                "members": {},
                "size": 0,
                "type": "struct"
            },
            "__main__.balance.HashBuiltin": {
                "destination": "starkware.cairo.common.cairo_builtins.HashBuiltin",
                "type": "alias"
            },
            "__main__.balance.ImplicitArgs": {
                "full_name": "__main__.balance.ImplicitArgs",
                "members": {},
                "size": 0,
                "type": "struct"
            },
            "__main__.balance.Return": {
                "cairo_type": "()",
                "type": "type_definition"
            },
            "__main__.balance.SIZEOF_LOCALS": {
                "type": "const",
                "value": 0
            },
            "__main__.balance.addr": {
                "decorators": [],
                "pc": 20,
                "type": "function"
            },
            "__main__.balance.addr.Args": {
                "full_name": "__main__.balance.addr.Args",
                "members": {},
                "size": 0,
                "type": "struct"
            },
            "__main__.balance.addr.ImplicitArgs": {
                "full_name": "__main__.balance.addr.ImplicitArgs",
                "members": {
                    "pedersen_ptr": {
                        "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                        "offset": 0
                    },
                    "range_check_ptr": {
                        "cairo_type": "felt",
                        "offset": 1
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "__main__.balance.addr.Return": {
                "cairo_type": "(res: felt)",
                "type": "type_definition"
            },
            "__main__.balance.addr.SIZEOF_LOCALS": {
                "type": "const",
                "value": 0
            },
            "__main__.balance.addr.pedersen_ptr": {
                "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                "full_name": "__main__.balance.addr.pedersen_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 3,
                            "offset": 0
                        },
                        "pc": 20,
                        "value": "[cast(fp + (-4), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.balance.addr.range_check_ptr": {
                "cairo_type": "felt",
                "full_name": "__main__.balance.addr.range_check_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 3,
                            "offset": 0
                        },
                        "pc": 20,
                        "value": "[cast(fp + (-3), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.balance.addr.res": {
                "cairo_type": "felt",
                "full_name": "__main__.balance.addr.res",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 3,
                            "offset": 0
                        },
                        "pc": 20,
                        "value": "cast(916907772491729262376534102982219947830828984996257231353398618781993312401, felt)"
                    }
                ],
                "type": "reference"
            },
            "__main__.balance.hash2": {
                "destination": "starkware.cairo.common.hash.hash2",
                "type": "alias"
            },
            "__main__.balance.normalize_address": {
                "destination": "starkware.starknet.common.storage.normalize_address",
                "type": "alias"
            },
            "__main__.balance.read": {
                "decorators": [],
                "pc": 25,
                "type": "function"
            },
            "__main__.balance.read.Args": {
                "full_name": "__main__.balance.read.Args",
                "members": {},
                "size": 0,
                "type": "struct"
            },
            "__main__.balance.read.ImplicitArgs": {
                "full_name": "__main__.balance.read.ImplicitArgs",
                "members": {
                    "pedersen_ptr": {
                        "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                        "offset": 1
                    },
                    "range_check_ptr": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "syscall_ptr": {
                        "cairo_type": "felt*",
                        "offset": 0
                    }
                },
                "size": 3,
                "type": "struct"
            },
            "__main__.balance.read.Return": {
                "cairo_type": "(res: felt)",
                "type": "type_definition"
            },
            "__main__.balance.read.SIZEOF_LOCALS": {
                "type": "const",
                "value": 0
            },
            "__main__.balance.read.__storage_var_temp0": {
                "cairo_type": "felt",
                "full_name": "__main__.balance.read.__storage_var_temp0",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 4,
                            "offset": 14
                        },
                        "pc": 33,
                        "value": "[cast(ap + (-1), felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 4,
                            "offset": 18
                        },
                        "pc": 37,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.balance.read.pedersen_ptr": {
                "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                "full_name": "__main__.balance.read.pedersen_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 4,
                            "offset": 0
                        },
                        "pc": 25,
                        "value": "[cast(fp + (-4), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 4,
                            "offset": 7
                        },
                        "pc": 29,
                        "value": "[cast(ap + (-3), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 4,
                            "offset": 16
                        },
                        "pc": 35,
                        "value": "[cast(ap + (-1), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.balance.read.range_check_ptr": {
                "cairo_type": "felt",
                "full_name": "__main__.balance.read.range_check_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 4,
                            "offset": 0
                        },
                        "pc": 25,
                        "value": "[cast(fp + (-3), felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 4,
                            "offset": 7
                        },
                        "pc": 29,
                        "value": "[cast(ap + (-2), felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 4,
                            "offset": 17
                        },
                        "pc": 36,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.balance.read.storage_addr": {
                "cairo_type": "felt",
                "full_name": "__main__.balance.read.storage_addr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 4,
                            "offset": 7
                        },
                        "pc": 29,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.balance.read.syscall_ptr": {
                "cairo_type": "felt*",
                "full_name": "__main__.balance.read.syscall_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 4,
                            "offset": 0
                        },
                        "pc": 25,
                        "value": "[cast(fp + (-5), felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 4,
                            "offset": 14
                        },
                        "pc": 33,
                        "value": "[cast(ap + (-2), felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 4,
                            "offset": 15
                        },
                        "pc": 34,
                        "value": "[cast(ap + (-1), felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.balance.storage_read": {
                "destination": "starkware.starknet.common.syscalls.storage_read",
                "type": "alias"
            },
            "__main__.balance.storage_write": {
                "destination": "starkware.starknet.common.syscalls.storage_write",
                "type": "alias"
            },
            "__main__.balance.write": {
                "decorators": [],
                "pc": 38,
                "type": "function"
            },
            "__main__.balance.write.Args": {
                "full_name": "__main__.balance.write.Args",
                "members": {
                    "value": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "__main__.balance.write.ImplicitArgs": {
                "full_name": "__main__.balance.write.ImplicitArgs",
                "members": {
                    "pedersen_ptr": {
                        "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                        "offset": 1
                    },
                    "range_check_ptr": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "syscall_ptr": {
                        "cairo_type": "felt*",
                        "offset": 0
                    }
                },
                "size": 3,
                "type": "struct"
            },
            "__main__.balance.write.Return": {
                "cairo_type": "()",
                "type": "type_definition"
            },
            "__main__.balance.write.SIZEOF_LOCALS": {
                "type": "const",
                "value": 0
            },
            "__main__.balance.write.pedersen_ptr": {
                "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                "full_name": "__main__.balance.write.pedersen_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 5,
                            "offset": 0
                        },
                        "pc": 38,
                        "value": "[cast(fp + (-5), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 5,
                            "offset": 7
                        },
                        "pc": 42,
                        "value": "[cast(ap + (-3), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.balance.write.range_check_ptr": {
                "cairo_type": "felt",
                "full_name": "__main__.balance.write.range_check_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 5,
                            "offset": 0
                        },
                        "pc": 38,
                        "value": "[cast(fp + (-4), felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 5,
                            "offset": 7
                        },
                        "pc": 42,
                        "value": "[cast(ap + (-2), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.balance.write.storage_addr": {
                "cairo_type": "felt",
                "full_name": "__main__.balance.write.storage_addr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 5,
                            "offset": 7
                        },
                        "pc": 42,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.balance.write.syscall_ptr": {
                "cairo_type": "felt*",
                "full_name": "__main__.balance.write.syscall_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 5,
                            "offset": 0
                        },
                        "pc": 38,
                        "value": "[cast(fp + (-6), felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 5,
                            "offset": 14
                        },
                        "pc": 47,
                        "value": "[cast(ap + (-1), felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.balance.write.value": {
                "cairo_type": "felt",
                "full_name": "__main__.balance.write.value",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 5,
                            "offset": 0
                        },
                        "pc": 38,
                        "value": "[cast(fp + (-3), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.constructor": {
                "decorators": [
                    "constructor"
                ],
                "pc": 114,
                "type": "function"
            },
            "__main__.constructor.Args": {
                "full_name": "__main__.constructor.Args",
                "members": {},
                "size": 0,
                "type": "struct"
            },
            "__main__.constructor.ImplicitArgs": {
                "full_name": "__main__.constructor.ImplicitArgs",
                "members": {
                    "pedersen_ptr": {
                        "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                        "offset": 1
                    },
                    "range_check_ptr": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "syscall_ptr": {
                        "cairo_type": "felt*",
                        "offset": 0
                    }
                },
                "size": 3,
                "type": "struct"
            },
            "__main__.constructor.Return": {
                "cairo_type": "()",
                "type": "type_definition"
            },
            "__main__.constructor.SIZEOF_LOCALS": {
                "type": "const",
                "value": 0
            },
            "__main__.constructor.pedersen_ptr": {
                "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                "full_name": "__main__.constructor.pedersen_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 11,
                            "offset": 0
                        },
                        "pc": 114,
                        "value": "[cast(fp + (-4), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 11,
                            "offset": 22
                        },
                        "pc": 121,
                        "value": "[cast(ap + (-2), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.constructor.range_check_ptr": {
                "cairo_type": "felt",
                "full_name": "__main__.constructor.range_check_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 11,
                            "offset": 0
                        },
                        "pc": 114,
                        "value": "[cast(fp + (-3), felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 11,
                            "offset": 22
                        },
                        "pc": 121,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.constructor.syscall_ptr": {
                "cairo_type": "felt*",
                "full_name": "__main__.constructor.syscall_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 11,
                            "offset": 0
                        },
                        "pc": 114,
                        "value": "[cast(fp + (-5), felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 11,
                            "offset": 22
                        },
                        "pc": 121,
                        "value": "[cast(ap + (-3), felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.get_balance": {
                "decorators": [
                    "view"
                ],
                "pc": 84,
                "type": "function"
            },
            "__main__.get_balance.Args": {
                "full_name": "__main__.get_balance.Args",
                "members": {},
                "size": 0,
                "type": "struct"
            },
            "__main__.get_balance.ImplicitArgs": {
                "full_name": "__main__.get_balance.ImplicitArgs",
                "members": {
                    "pedersen_ptr": {
                        "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                        "offset": 1
                    },
                    "range_check_ptr": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "syscall_ptr": {
                        "cairo_type": "felt*",
                        "offset": 0
                    }
                },
                "size": 3,
                "type": "struct"
            },
            "__main__.get_balance.Return": {
                "cairo_type": "(res: felt)",
                "type": "type_definition"
            },
            "__main__.get_balance.SIZEOF_LOCALS": {
                "type": "const",
                "value": 0
            },
            "__main__.get_balance.pedersen_ptr": {
                "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                "full_name": "__main__.get_balance.pedersen_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 8,
                            "offset": 0
                        },
                        "pc": 84,
                        "value": "[cast(fp + (-4), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 8,
                            "offset": 23
                        },
                        "pc": 89,
                        "value": "[cast(ap + (-3), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.get_balance.range_check_ptr": {
                "cairo_type": "felt",
                "full_name": "__main__.get_balance.range_check_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 8,
                            "offset": 0
                        },
                        "pc": 84,
                        "value": "[cast(fp + (-3), felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 8,
                            "offset": 23
                        },
                        "pc": 89,
                        "value": "[cast(ap + (-2), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.get_balance.res": {
                "cairo_type": "felt",
                "full_name": "__main__.get_balance.res",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 8,
                            "offset": 23
                        },
                        "pc": 89,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.get_balance.syscall_ptr": {
                "cairo_type": "felt*",
                "full_name": "__main__.get_balance.syscall_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 8,
                            "offset": 0
                        },
                        "pc": 84,
                        "value": "[cast(fp + (-5), felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 8,
                            "offset": 23
                        },
                        "pc": 89,
                        "value": "[cast(ap + (-4), felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.increase_balance": {
                "decorators": [
                    "external"
                ],
                "pc": 50,
                "type": "function"
            },
            "__main__.increase_balance.Args": {
                "full_name": "__main__.increase_balance.Args",
                "members": {
                    "amount": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "__main__.increase_balance.ImplicitArgs": {
                "full_name": "__main__.increase_balance.ImplicitArgs",
                "members": {
                    "pedersen_ptr": {
                        "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                        "offset": 1
                    },
                    "range_check_ptr": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "syscall_ptr": {
                        "cairo_type": "felt*",
                        "offset": 0
                    }
                },
                "size": 3,
                "type": "struct"
            },
            "__main__.increase_balance.Return": {
                "cairo_type": "()",
                "type": "type_definition"
            },
            "__main__.increase_balance.SIZEOF_LOCALS": {
                "type": "const",
                "value": 0
            },
            "__main__.increase_balance.amount": {
                "cairo_type": "felt",
                "full_name": "__main__.increase_balance.amount",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 6,
                            "offset": 0
                        },
                        "pc": 50,
                        "value": "[cast(fp + (-3), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.increase_balance.pedersen_ptr": {
                "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                "full_name": "__main__.increase_balance.pedersen_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 6,
                            "offset": 0
                        },
                        "pc": 50,
                        "value": "[cast(fp + (-5), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 6,
                            "offset": 28
                        },
                        "pc": 59,
                        "value": "[cast(ap + (-3), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 6,
                            "offset": 50
                        },
                        "pc": 65,
                        "value": "[cast(ap + (-2), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.increase_balance.range_check_ptr": {
                "cairo_type": "felt",
                "full_name": "__main__.increase_balance.range_check_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 6,
                            "offset": 0
                        },
                        "pc": 50,
                        "value": "[cast(fp + (-4), felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 6,
                            "offset": 5
                        },
                        "pc": 54,
                        "value": "[cast(ap + (-1), felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 6,
                            "offset": 28
                        },
                        "pc": 59,
                        "value": "[cast(ap + (-2), felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 6,
                            "offset": 50
                        },
                        "pc": 65,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.increase_balance.res": {
                "cairo_type": "felt",
                "full_name": "__main__.increase_balance.res",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 6,
                            "offset": 28
                        },
                        "pc": 59,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__main__.increase_balance.syscall_ptr": {
                "cairo_type": "felt*",
                "full_name": "__main__.increase_balance.syscall_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 6,
                            "offset": 0
                        },
                        "pc": 50,
                        "value": "[cast(fp + (-6), felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 6,
                            "offset": 28
                        },
                        "pc": 59,
                        "value": "[cast(ap + (-4), felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 6,
                            "offset": 50
                        },
                        "pc": 65,
                        "value": "[cast(ap + (-3), felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.constructor": {
                "decorators": [
                    "constructor"
                ],
                "pc": 122,
                "type": "function"
            },
            "__wrappers__.constructor.Args": {
                "full_name": "__wrappers__.constructor.Args",
                "members": {},
                "size": 0,
                "type": "struct"
            },
            "__wrappers__.constructor.ImplicitArgs": {
                "full_name": "__wrappers__.constructor.ImplicitArgs",
                "members": {},
                "size": 0,
                "type": "struct"
            },
            "__wrappers__.constructor.Return": {
                "cairo_type": "(syscall_ptr: felt*, pedersen_ptr: starkware.cairo.common.cairo_builtins.HashBuiltin*, range_check_ptr: felt, size: felt, retdata: felt*)",
                "type": "type_definition"
            },
            "__wrappers__.constructor.SIZEOF_LOCALS": {
                "type": "const",
                "value": 0
            },
            "__wrappers__.constructor.__calldata_actual_size": {
                "cairo_type": "felt",
                "full_name": "__wrappers__.constructor.__calldata_actual_size",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 12,
                            "offset": 0
                        },
                        "pc": 122,
                        "value": "cast([fp + (-3)] - [fp + (-3)], felt)"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.constructor.__calldata_ptr": {
                "cairo_type": "felt*",
                "full_name": "__wrappers__.constructor.__calldata_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 12,
                            "offset": 0
                        },
                        "pc": 122,
                        "value": "[cast(fp + (-3), felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.constructor.__wrapped_func": {
                "destination": "__main__.constructor",
                "type": "alias"
            },
            "__wrappers__.constructor.pedersen_ptr": {
                "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                "full_name": "__wrappers__.constructor.pedersen_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 12,
                            "offset": 0
                        },
                        "pc": 122,
                        "value": "[cast([fp + (-5)] + 1, starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 12,
                            "offset": 27
                        },
                        "pc": 128,
                        "value": "[cast(ap + (-2), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.constructor.range_check_ptr": {
                "cairo_type": "felt",
                "full_name": "__wrappers__.constructor.range_check_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 12,
                            "offset": 0
                        },
                        "pc": 122,
                        "value": "[cast([fp + (-5)] + 2, felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 12,
                            "offset": 27
                        },
                        "pc": 128,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.constructor.ret_value": {
                "cairo_type": "()",
                "full_name": "__wrappers__.constructor.ret_value",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 12,
                            "offset": 27
                        },
                        "pc": 128,
                        "value": "[cast(ap + 0, ()*)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.constructor.retdata": {
                "cairo_type": "felt*",
                "full_name": "__wrappers__.constructor.retdata",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 12,
                            "offset": 28
                        },
                        "pc": 130,
                        "value": "[cast(ap + (-1), felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.constructor.retdata_size": {
                "cairo_type": "felt",
                "full_name": "__wrappers__.constructor.retdata_size",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 12,
                            "offset": 28
                        },
                        "pc": 130,
                        "value": "cast(0, felt)"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.constructor.syscall_ptr": {
                "cairo_type": "felt*",
                "full_name": "__wrappers__.constructor.syscall_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 12,
                            "offset": 0
                        },
                        "pc": 122,
                        "value": "[cast([fp + (-5)], felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 12,
                            "offset": 27
                        },
                        "pc": 128,
                        "value": "[cast(ap + (-3), felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.constructor_encode_return.memcpy": {
                "destination": "starkware.cairo.common.memcpy.memcpy",
                "type": "alias"
            },
            "__wrappers__.get_balance": {
                "decorators": [
                    "view"
                ],
                "pc": 99,
                "type": "function"
            },
            "__wrappers__.get_balance.Args": {
                "full_name": "__wrappers__.get_balance.Args",
                "members": {},
                "size": 0,
                "type": "struct"
            },
            "__wrappers__.get_balance.ImplicitArgs": {
                "full_name": "__wrappers__.get_balance.ImplicitArgs",
                "members": {},
                "size": 0,
                "type": "struct"
            },
            "__wrappers__.get_balance.Return": {
                "cairo_type": "(syscall_ptr: felt*, pedersen_ptr: starkware.cairo.common.cairo_builtins.HashBuiltin*, range_check_ptr: felt, size: felt, retdata: felt*)",
                "type": "type_definition"
            },
            "__wrappers__.get_balance.SIZEOF_LOCALS": {
                "type": "const",
                "value": 0
            },
            "__wrappers__.get_balance.__calldata_actual_size": {
                "cairo_type": "felt",
                "full_name": "__wrappers__.get_balance.__calldata_actual_size",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 10,
                            "offset": 0
                        },
                        "pc": 99,
                        "value": "cast([fp + (-3)] - [fp + (-3)], felt)"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.get_balance.__calldata_ptr": {
                "cairo_type": "felt*",
                "full_name": "__wrappers__.get_balance.__calldata_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 10,
                            "offset": 0
                        },
                        "pc": 99,
                        "value": "[cast(fp + (-3), felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.get_balance.__wrapped_func": {
                "destination": "__main__.get_balance",
                "type": "alias"
            },
            "__wrappers__.get_balance.pedersen_ptr": {
                "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                "full_name": "__wrappers__.get_balance.pedersen_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 10,
                            "offset": 0
                        },
                        "pc": 99,
                        "value": "[cast([fp + (-5)] + 1, starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 10,
                            "offset": 28
                        },
                        "pc": 105,
                        "value": "[cast(ap + (-3), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.get_balance.range_check_ptr": {
                "cairo_type": "felt",
                "full_name": "__wrappers__.get_balance.range_check_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 10,
                            "offset": 0
                        },
                        "pc": 99,
                        "value": "[cast([fp + (-5)] + 2, felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 10,
                            "offset": 28
                        },
                        "pc": 105,
                        "value": "[cast(ap + (-2), felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 10,
                            "offset": 36
                        },
                        "pc": 108,
                        "value": "[cast(ap + (-3), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.get_balance.ret_value": {
                "cairo_type": "(res: felt)",
                "full_name": "__wrappers__.get_balance.ret_value",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 10,
                            "offset": 28
                        },
                        "pc": 105,
                        "value": "[cast(ap + (-1), (res: felt)*)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.get_balance.retdata": {
                "cairo_type": "felt*",
                "full_name": "__wrappers__.get_balance.retdata",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 10,
                            "offset": 36
                        },
                        "pc": 108,
                        "value": "[cast(ap + (-1), felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.get_balance.retdata_size": {
                "cairo_type": "felt",
                "full_name": "__wrappers__.get_balance.retdata_size",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 10,
                            "offset": 36
                        },
                        "pc": 108,
                        "value": "[cast(ap + (-2), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.get_balance.syscall_ptr": {
                "cairo_type": "felt*",
                "full_name": "__wrappers__.get_balance.syscall_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 10,
                            "offset": 0
                        },
                        "pc": 99,
                        "value": "[cast([fp + (-5)], felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 10,
                            "offset": 28
                        },
                        "pc": 105,
                        "value": "[cast(ap + (-4), felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.get_balance_encode_return": {
                "decorators": [],
                "pc": 90,
                "type": "function"
            },
            "__wrappers__.get_balance_encode_return.Args": {
                "full_name": "__wrappers__.get_balance_encode_return.Args",
                "members": {
                    "range_check_ptr": {
                        "cairo_type": "felt",
                        "offset": 1
                    },
                    "ret_value": {
                        "cairo_type": "(res: felt)",
                        "offset": 0
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "__wrappers__.get_balance_encode_return.ImplicitArgs": {
                "full_name": "__wrappers__.get_balance_encode_return.ImplicitArgs",
                "members": {},
                "size": 0,
                "type": "struct"
            },
            "__wrappers__.get_balance_encode_return.Return": {
                "cairo_type": "(range_check_ptr: felt, data_len: felt, data: felt*)",
                "type": "type_definition"
            },
            "__wrappers__.get_balance_encode_return.SIZEOF_LOCALS": {
                "type": "const",
                "value": 1
            },
            "__wrappers__.get_balance_encode_return.__return_value_ptr": {
                "cairo_type": "felt*",
                "full_name": "__wrappers__.get_balance_encode_return.__return_value_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 9,
                            "offset": 1
                        },
                        "pc": 92,
                        "value": "[cast(fp, felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 9,
                            "offset": 1
                        },
                        "pc": 93,
                        "value": "cast([fp] + 1, felt*)"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.get_balance_encode_return.__return_value_ptr_start": {
                "cairo_type": "felt*",
                "full_name": "__wrappers__.get_balance_encode_return.__return_value_ptr_start",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 9,
                            "offset": 1
                        },
                        "pc": 92,
                        "value": "[cast(fp, felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.get_balance_encode_return.__temp3": {
                "cairo_type": "felt",
                "full_name": "__wrappers__.get_balance_encode_return.__temp3",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 9,
                            "offset": 2
                        },
                        "pc": 95,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.get_balance_encode_return.memcpy": {
                "destination": "starkware.cairo.common.memcpy.memcpy",
                "type": "alias"
            },
            "__wrappers__.get_balance_encode_return.range_check_ptr": {
                "cairo_type": "felt",
                "full_name": "__wrappers__.get_balance_encode_return.range_check_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 9,
                            "offset": 0
                        },
                        "pc": 90,
                        "value": "[cast(fp + (-3), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.get_balance_encode_return.ret_value": {
                "cairo_type": "(res: felt)",
                "full_name": "__wrappers__.get_balance_encode_return.ret_value",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 9,
                            "offset": 0
                        },
                        "pc": 90,
                        "value": "[cast(fp + (-4), (res: felt)*)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.increase_balance": {
                "decorators": [
                    "external"
                ],
                "pc": 66,
                "type": "function"
            },
            "__wrappers__.increase_balance.Args": {
                "full_name": "__wrappers__.increase_balance.Args",
                "members": {},
                "size": 0,
                "type": "struct"
            },
            "__wrappers__.increase_balance.ImplicitArgs": {
                "full_name": "__wrappers__.increase_balance.ImplicitArgs",
                "members": {},
                "size": 0,
                "type": "struct"
            },
            "__wrappers__.increase_balance.Return": {
                "cairo_type": "(syscall_ptr: felt*, pedersen_ptr: starkware.cairo.common.cairo_builtins.HashBuiltin*, range_check_ptr: felt, size: felt, retdata: felt*)",
                "type": "type_definition"
            },
            "__wrappers__.increase_balance.SIZEOF_LOCALS": {
                "type": "const",
                "value": 0
            },
            "__wrappers__.increase_balance.__calldata_actual_size": {
                "cairo_type": "felt",
                "full_name": "__wrappers__.increase_balance.__calldata_actual_size",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 0
                        },
                        "pc": 66,
                        "value": "cast([fp + (-3)] + 1 - [fp + (-3)], felt)"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.increase_balance.__calldata_arg_amount": {
                "cairo_type": "felt",
                "full_name": "__wrappers__.increase_balance.__calldata_arg_amount",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 0
                        },
                        "pc": 66,
                        "value": "[cast([fp + (-3)], felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.increase_balance.__calldata_ptr": {
                "cairo_type": "felt*",
                "full_name": "__wrappers__.increase_balance.__calldata_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 0
                        },
                        "pc": 66,
                        "value": "[cast(fp + (-3), felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 0
                        },
                        "pc": 66,
                        "value": "cast([fp + (-3)] + 1, felt*)"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.increase_balance.__temp2": {
                "cairo_type": "felt",
                "full_name": "__wrappers__.increase_balance.__temp2",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 1
                        },
                        "pc": 68,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.increase_balance.__wrapped_func": {
                "destination": "__main__.increase_balance",
                "type": "alias"
            },
            "__wrappers__.increase_balance.pedersen_ptr": {
                "cairo_type": "starkware.cairo.common.cairo_builtins.HashBuiltin*",
                "full_name": "__wrappers__.increase_balance.pedersen_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 0
                        },
                        "pc": 66,
                        "value": "[cast([fp + (-5)] + 1, starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 57
                        },
                        "pc": 75,
                        "value": "[cast(ap + (-2), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.increase_balance.range_check_ptr": {
                "cairo_type": "felt",
                "full_name": "__wrappers__.increase_balance.range_check_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 0
                        },
                        "pc": 66,
                        "value": "[cast([fp + (-5)] + 2, felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 57
                        },
                        "pc": 75,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.increase_balance.ret_value": {
                "cairo_type": "()",
                "full_name": "__wrappers__.increase_balance.ret_value",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 57
                        },
                        "pc": 75,
                        "value": "[cast(ap + 0, ()*)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.increase_balance.retdata": {
                "cairo_type": "felt*",
                "full_name": "__wrappers__.increase_balance.retdata",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 58
                        },
                        "pc": 77,
                        "value": "[cast(ap + (-1), felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.increase_balance.retdata_size": {
                "cairo_type": "felt",
                "full_name": "__wrappers__.increase_balance.retdata_size",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 58
                        },
                        "pc": 77,
                        "value": "cast(0, felt)"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.increase_balance.syscall_ptr": {
                "cairo_type": "felt*",
                "full_name": "__wrappers__.increase_balance.syscall_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 0
                        },
                        "pc": 66,
                        "value": "[cast([fp + (-5)], felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 7,
                            "offset": 57
                        },
                        "pc": 75,
                        "value": "[cast(ap + (-3), felt**)]"
                    }
                ],
                "type": "reference"
            },
            "__wrappers__.increase_balance_encode_return.memcpy": {
                "destination": "starkware.cairo.common.memcpy.memcpy",
                "type": "alias"
            },
            "starkware.cairo.common.bool.FALSE": {
                "type": "const",
                "value": 0
            },
            "starkware.cairo.common.bool.TRUE": {
                "type": "const",
                "value": 1
            },
            "starkware.cairo.common.cairo_builtins.BitwiseBuiltin": {
                "full_name": "starkware.cairo.common.cairo_builtins.BitwiseBuiltin",
                "members": {
                    "x": {
                        "cairo_type": "felt",
                        "offset": 0
                    },
                    "x_and_y": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "x_or_y": {
                        "cairo_type": "felt",
                        "offset": 4
                    },
                    "x_xor_y": {
                        "cairo_type": "felt",
                        "offset": 3
                    },
                    "y": {
                        "cairo_type": "felt",
                        "offset": 1
                    }
                },
                "size": 5,
                "type": "struct"
            },
            "starkware.cairo.common.cairo_builtins.EcOpBuiltin": {
                "full_name": "starkware.cairo.common.cairo_builtins.EcOpBuiltin",
                "members": {
                    "m": {
                        "cairo_type": "felt",
                        "offset": 4
                    },
                    "p": {
                        "cairo_type": "starkware.cairo.common.ec_point.EcPoint",
                        "offset": 0
                    },
                    "q": {
                        "cairo_type": "starkware.cairo.common.ec_point.EcPoint",
                        "offset": 2
                    },
                    "r": {
                        "cairo_type": "starkware.cairo.common.ec_point.EcPoint",
                        "offset": 5
                    }
                },
                "size": 7,
                "type": "struct"
            },
            "starkware.cairo.common.cairo_builtins.EcPoint": {
                "destination": "starkware.cairo.common.ec_point.EcPoint",
                "type": "alias"
            },
            "starkware.cairo.common.cairo_builtins.HashBuiltin": {
                "full_name": "starkware.cairo.common.cairo_builtins.HashBuiltin",
                "members": {
                    "result": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "x": {
                        "cairo_type": "felt",
                        "offset": 0
                    },
                    "y": {
                        "cairo_type": "felt",
                        "offset": 1
                    }
                },
                "size": 3,
                "type": "struct"
            },
            "starkware.cairo.common.cairo_builtins.KeccakBuiltin": {
                "full_name": "starkware.cairo.common.cairo_builtins.KeccakBuiltin",
                "members": {
                    "input": {
                        "cairo_type": "starkware.cairo.common.keccak_state.KeccakBuiltinState",
                        "offset": 0
                    },
                    "output": {
                        "cairo_type": "starkware.cairo.common.keccak_state.KeccakBuiltinState",
                        "offset": 8
                    }
                },
                "size": 16,
                "type": "struct"
            },
            "starkware.cairo.common.cairo_builtins.KeccakBuiltinState": {
                "destination": "starkware.cairo.common.keccak_state.KeccakBuiltinState",
                "type": "alias"
            },
            "starkware.cairo.common.cairo_builtins.SignatureBuiltin": {
                "full_name": "starkware.cairo.common.cairo_builtins.SignatureBuiltin",
                "members": {
                    "message": {
                        "cairo_type": "felt",
                        "offset": 1
                    },
                    "pub_key": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "starkware.cairo.common.dict_access.DictAccess": {
                "full_name": "starkware.cairo.common.dict_access.DictAccess",
                "members": {
                    "key": {
                        "cairo_type": "felt",
                        "offset": 0
                    },
                    "new_value": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "prev_value": {
                        "cairo_type": "felt",
                        "offset": 1
                    }
                },
                "size": 3,
                "type": "struct"
            },
            "starkware.cairo.common.ec_point.EcPoint": {
                "full_name": "starkware.cairo.common.ec_point.EcPoint",
                "members": {
                    "x": {
                        "cairo_type": "felt",
                        "offset": 0
                    },
                    "y": {
                        "cairo_type": "felt",
                        "offset": 1
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "starkware.cairo.common.hash.HashBuiltin": {
                "destination": "starkware.cairo.common.cairo_builtins.HashBuiltin",
                "type": "alias"
            },
            "starkware.cairo.common.keccak_state.KeccakBuiltinState": {
                "full_name": "starkware.cairo.common.keccak_state.KeccakBuiltinState",
                "members": {
                    "s0": {
                        "cairo_type": "felt",
                        "offset": 0
                    },
                    "s1": {
                        "cairo_type": "felt",
                        "offset": 1
                    },
                    "s2": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "s3": {
                        "cairo_type": "felt",
                        "offset": 3
                    },
                    "s4": {
                        "cairo_type": "felt",
                        "offset": 4
                    },
                    "s5": {
                        "cairo_type": "felt",
                        "offset": 5
                    },
                    "s6": {
                        "cairo_type": "felt",
                        "offset": 6
                    },
                    "s7": {
                        "cairo_type": "felt",
                        "offset": 7
                    }
                },
                "size": 8,
                "type": "struct"
            },
            "starkware.cairo.common.math.FALSE": {
                "destination": "starkware.cairo.common.bool.FALSE",
                "type": "alias"
            },
            "starkware.cairo.common.math.TRUE": {
                "destination": "starkware.cairo.common.bool.TRUE",
                "type": "alias"
            },
            "starkware.cairo.common.math.assert_nn": {
                "decorators": [],
                "pc": 0,
                "type": "function"
            },
            "starkware.cairo.common.math.assert_nn.Args": {
                "full_name": "starkware.cairo.common.math.assert_nn.Args",
                "members": {
                    "a": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.cairo.common.math.assert_nn.ImplicitArgs": {
                "full_name": "starkware.cairo.common.math.assert_nn.ImplicitArgs",
                "members": {
                    "range_check_ptr": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.cairo.common.math.assert_nn.Return": {
                "cairo_type": "()",
                "type": "type_definition"
            },
            "starkware.cairo.common.math.assert_nn.SIZEOF_LOCALS": {
                "type": "const",
                "value": 0
            },
            "starkware.cairo.common.math.assert_nn.a": {
                "cairo_type": "felt",
                "full_name": "starkware.cairo.common.math.assert_nn.a",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 0,
                            "offset": 0
                        },
                        "pc": 0,
                        "value": "[cast(fp + (-3), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "starkware.cairo.common.math.assert_nn.range_check_ptr": {
                "cairo_type": "felt",
                "full_name": "starkware.cairo.common.math.assert_nn.range_check_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 0,
                            "offset": 0
                        },
                        "pc": 0,
                        "value": "[cast(fp + (-4), felt*)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 0,
                            "offset": 0
                        },
                        "pc": 1,
                        "value": "cast([fp + (-4)] + 1, felt)"
                    }
                ],
                "type": "reference"
            },
            "starkware.starknet.common.storage.ADDR_BOUND": {
                "type": "const",
                "value": -106710729501573572985208420194530329073740042555888586719489
            },
            "starkware.starknet.common.storage.MAX_STORAGE_ITEM_SIZE": {
                "type": "const",
                "value": 256
            },
            "starkware.starknet.common.storage.assert_250_bit": {
                "destination": "starkware.cairo.common.math.assert_250_bit",
                "type": "alias"
            },
            "starkware.starknet.common.syscalls.CALL_CONTRACT_SELECTOR": {
                "type": "const",
                "value": 20853273475220472486191784820
            },
            "starkware.starknet.common.syscalls.CallContract": {
                "full_name": "starkware.starknet.common.syscalls.CallContract",
                "members": {
                    "request": {
                        "cairo_type": "starkware.starknet.common.syscalls.CallContractRequest",
                        "offset": 0
                    },
                    "response": {
                        "cairo_type": "starkware.starknet.common.syscalls.CallContractResponse",
                        "offset": 5
                    }
                },
                "size": 7,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.CallContractRequest": {
                "full_name": "starkware.starknet.common.syscalls.CallContractRequest",
                "members": {
                    "calldata": {
                        "cairo_type": "felt*",
                        "offset": 4
                    },
                    "calldata_size": {
                        "cairo_type": "felt",
                        "offset": 3
                    },
                    "contract_address": {
                        "cairo_type": "felt",
                        "offset": 1
                    },
                    "function_selector": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 5,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.CallContractResponse": {
                "full_name": "starkware.starknet.common.syscalls.CallContractResponse",
                "members": {
                    "retdata": {
                        "cairo_type": "felt*",
                        "offset": 1
                    },
                    "retdata_size": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.DELEGATE_CALL_SELECTOR": {
                "type": "const",
                "value": 21167594061783206823196716140
            },
            "starkware.starknet.common.syscalls.DELEGATE_L1_HANDLER_SELECTOR": {
                "type": "const",
                "value": 23274015802972845247556842986379118667122
            },
            "starkware.starknet.common.syscalls.DEPLOY_SELECTOR": {
                "type": "const",
                "value": 75202468540281
            },
            "starkware.starknet.common.syscalls.Deploy": {
                "full_name": "starkware.starknet.common.syscalls.Deploy",
                "members": {
                    "request": {
                        "cairo_type": "starkware.starknet.common.syscalls.DeployRequest",
                        "offset": 0
                    },
                    "response": {
                        "cairo_type": "starkware.starknet.common.syscalls.DeployResponse",
                        "offset": 6
                    }
                },
                "size": 9,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.DeployRequest": {
                "full_name": "starkware.starknet.common.syscalls.DeployRequest",
                "members": {
                    "class_hash": {
                        "cairo_type": "felt",
                        "offset": 1
                    },
                    "constructor_calldata": {
                        "cairo_type": "felt*",
                        "offset": 4
                    },
                    "constructor_calldata_size": {
                        "cairo_type": "felt",
                        "offset": 3
                    },
                    "contract_address_salt": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "deploy_from_zero": {
                        "cairo_type": "felt",
                        "offset": 5
                    },
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 6,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.DeployResponse": {
                "full_name": "starkware.starknet.common.syscalls.DeployResponse",
                "members": {
                    "constructor_retdata": {
                        "cairo_type": "felt*",
                        "offset": 2
                    },
                    "constructor_retdata_size": {
                        "cairo_type": "felt",
                        "offset": 1
                    },
                    "contract_address": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 3,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.DictAccess": {
                "destination": "starkware.cairo.common.dict_access.DictAccess",
                "type": "alias"
            },
            "starkware.starknet.common.syscalls.EMIT_EVENT_SELECTOR": {
                "type": "const",
                "value": 1280709301550335749748
            },
            "starkware.starknet.common.syscalls.EmitEvent": {
                "full_name": "starkware.starknet.common.syscalls.EmitEvent",
                "members": {
                    "data": {
                        "cairo_type": "felt*",
                        "offset": 4
                    },
                    "data_len": {
                        "cairo_type": "felt",
                        "offset": 3
                    },
                    "keys": {
                        "cairo_type": "felt*",
                        "offset": 2
                    },
                    "keys_len": {
                        "cairo_type": "felt",
                        "offset": 1
                    },
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 5,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GET_BLOCK_NUMBER_SELECTOR": {
                "type": "const",
                "value": 1448089106835523001438702345020786
            },
            "starkware.starknet.common.syscalls.GET_BLOCK_TIMESTAMP_SELECTOR": {
                "type": "const",
                "value": 24294903732626645868215235778792757751152
            },
            "starkware.starknet.common.syscalls.GET_CALLER_ADDRESS_SELECTOR": {
                "type": "const",
                "value": 94901967781393078444254803017658102643
            },
            "starkware.starknet.common.syscalls.GET_CONTRACT_ADDRESS_SELECTOR": {
                "type": "const",
                "value": 6219495360805491471215297013070624192820083
            },
            "starkware.starknet.common.syscalls.GET_SEQUENCER_ADDRESS_SELECTOR": {
                "type": "const",
                "value": 1592190833581991703053805829594610833820054387
            },
            "starkware.starknet.common.syscalls.GET_TX_INFO_SELECTOR": {
                "type": "const",
                "value": 1317029390204112103023
            },
            "starkware.starknet.common.syscalls.GET_TX_SIGNATURE_SELECTOR": {
                "type": "const",
                "value": 1448089128652340074717162277007973
            },
            "starkware.starknet.common.syscalls.GetBlockNumber": {
                "full_name": "starkware.starknet.common.syscalls.GetBlockNumber",
                "members": {
                    "request": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetBlockNumberRequest",
                        "offset": 0
                    },
                    "response": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetBlockNumberResponse",
                        "offset": 1
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetBlockNumberRequest": {
                "full_name": "starkware.starknet.common.syscalls.GetBlockNumberRequest",
                "members": {
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetBlockNumberResponse": {
                "full_name": "starkware.starknet.common.syscalls.GetBlockNumberResponse",
                "members": {
                    "block_number": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetBlockTimestamp": {
                "full_name": "starkware.starknet.common.syscalls.GetBlockTimestamp",
                "members": {
                    "request": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetBlockTimestampRequest",
                        "offset": 0
                    },
                    "response": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetBlockTimestampResponse",
                        "offset": 1
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetBlockTimestampRequest": {
                "full_name": "starkware.starknet.common.syscalls.GetBlockTimestampRequest",
                "members": {
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetBlockTimestampResponse": {
                "full_name": "starkware.starknet.common.syscalls.GetBlockTimestampResponse",
                "members": {
                    "block_timestamp": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetCallerAddress": {
                "full_name": "starkware.starknet.common.syscalls.GetCallerAddress",
                "members": {
                    "request": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetCallerAddressRequest",
                        "offset": 0
                    },
                    "response": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetCallerAddressResponse",
                        "offset": 1
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetCallerAddressRequest": {
                "full_name": "starkware.starknet.common.syscalls.GetCallerAddressRequest",
                "members": {
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetCallerAddressResponse": {
                "full_name": "starkware.starknet.common.syscalls.GetCallerAddressResponse",
                "members": {
                    "caller_address": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetContractAddress": {
                "full_name": "starkware.starknet.common.syscalls.GetContractAddress",
                "members": {
                    "request": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetContractAddressRequest",
                        "offset": 0
                    },
                    "response": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetContractAddressResponse",
                        "offset": 1
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetContractAddressRequest": {
                "full_name": "starkware.starknet.common.syscalls.GetContractAddressRequest",
                "members": {
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetContractAddressResponse": {
                "full_name": "starkware.starknet.common.syscalls.GetContractAddressResponse",
                "members": {
                    "contract_address": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetSequencerAddress": {
                "full_name": "starkware.starknet.common.syscalls.GetSequencerAddress",
                "members": {
                    "request": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetSequencerAddressRequest",
                        "offset": 0
                    },
                    "response": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetSequencerAddressResponse",
                        "offset": 1
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetSequencerAddressRequest": {
                "full_name": "starkware.starknet.common.syscalls.GetSequencerAddressRequest",
                "members": {
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetSequencerAddressResponse": {
                "full_name": "starkware.starknet.common.syscalls.GetSequencerAddressResponse",
                "members": {
                    "sequencer_address": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetTxInfo": {
                "full_name": "starkware.starknet.common.syscalls.GetTxInfo",
                "members": {
                    "request": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetTxInfoRequest",
                        "offset": 0
                    },
                    "response": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetTxInfoResponse",
                        "offset": 1
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetTxInfoRequest": {
                "full_name": "starkware.starknet.common.syscalls.GetTxInfoRequest",
                "members": {
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetTxInfoResponse": {
                "full_name": "starkware.starknet.common.syscalls.GetTxInfoResponse",
                "members": {
                    "tx_info": {
                        "cairo_type": "starkware.starknet.common.syscalls.TxInfo*",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetTxSignature": {
                "full_name": "starkware.starknet.common.syscalls.GetTxSignature",
                "members": {
                    "request": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetTxSignatureRequest",
                        "offset": 0
                    },
                    "response": {
                        "cairo_type": "starkware.starknet.common.syscalls.GetTxSignatureResponse",
                        "offset": 1
                    }
                },
                "size": 3,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetTxSignatureRequest": {
                "full_name": "starkware.starknet.common.syscalls.GetTxSignatureRequest",
                "members": {
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.GetTxSignatureResponse": {
                "full_name": "starkware.starknet.common.syscalls.GetTxSignatureResponse",
                "members": {
                    "signature": {
                        "cairo_type": "felt*",
                        "offset": 1
                    },
                    "signature_len": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.LIBRARY_CALL_L1_HANDLER_SELECTOR": {
                "type": "const",
                "value": 436233452754198157705746250789557519228244616562
            },
            "starkware.starknet.common.syscalls.LIBRARY_CALL_SELECTOR": {
                "type": "const",
                "value": 92376026794327011772951660
            },
            "starkware.starknet.common.syscalls.LibraryCall": {
                "full_name": "starkware.starknet.common.syscalls.LibraryCall",
                "members": {
                    "request": {
                        "cairo_type": "starkware.starknet.common.syscalls.LibraryCallRequest",
                        "offset": 0
                    },
                    "response": {
                        "cairo_type": "starkware.starknet.common.syscalls.CallContractResponse",
                        "offset": 5
                    }
                },
                "size": 7,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.LibraryCallRequest": {
                "full_name": "starkware.starknet.common.syscalls.LibraryCallRequest",
                "members": {
                    "calldata": {
                        "cairo_type": "felt*",
                        "offset": 4
                    },
                    "calldata_size": {
                        "cairo_type": "felt",
                        "offset": 3
                    },
                    "class_hash": {
                        "cairo_type": "felt",
                        "offset": 1
                    },
                    "function_selector": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 5,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.SEND_MESSAGE_TO_L1_SELECTOR": {
                "type": "const",
                "value": 433017908768303439907196859243777073
            },
            "starkware.starknet.common.syscalls.STORAGE_READ_SELECTOR": {
                "type": "const",
                "value": 100890693370601760042082660
            },
            "starkware.starknet.common.syscalls.STORAGE_WRITE_SELECTOR": {
                "type": "const",
                "value": 25828017502874050592466629733
            },
            "starkware.starknet.common.syscalls.SendMessageToL1SysCall": {
                "full_name": "starkware.starknet.common.syscalls.SendMessageToL1SysCall",
                "members": {
                    "payload_ptr": {
                        "cairo_type": "felt*",
                        "offset": 3
                    },
                    "payload_size": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    },
                    "to_address": {
                        "cairo_type": "felt",
                        "offset": 1
                    }
                },
                "size": 4,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.StorageRead": {
                "full_name": "starkware.starknet.common.syscalls.StorageRead",
                "members": {
                    "request": {
                        "cairo_type": "starkware.starknet.common.syscalls.StorageReadRequest",
                        "offset": 0
                    },
                    "response": {
                        "cairo_type": "starkware.starknet.common.syscalls.StorageReadResponse",
                        "offset": 2
                    }
                },
                "size": 3,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.StorageReadRequest": {
                "full_name": "starkware.starknet.common.syscalls.StorageReadRequest",
                "members": {
                    "address": {
                        "cairo_type": "felt",
                        "offset": 1
                    },
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.StorageReadResponse": {
                "full_name": "starkware.starknet.common.syscalls.StorageReadResponse",
                "members": {
                    "value": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.StorageWrite": {
                "full_name": "starkware.starknet.common.syscalls.StorageWrite",
                "members": {
                    "address": {
                        "cairo_type": "felt",
                        "offset": 1
                    },
                    "selector": {
                        "cairo_type": "felt",
                        "offset": 0
                    },
                    "value": {
                        "cairo_type": "felt",
                        "offset": 2
                    }
                },
                "size": 3,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.TxInfo": {
                "full_name": "starkware.starknet.common.syscalls.TxInfo",
                "members": {
                    "account_contract_address": {
                        "cairo_type": "felt",
                        "offset": 1
                    },
                    "chain_id": {
                        "cairo_type": "felt",
                        "offset": 6
                    },
                    "max_fee": {
                        "cairo_type": "felt",
                        "offset": 2
                    },
                    "nonce": {
                        "cairo_type": "felt",
                        "offset": 7
                    },
                    "signature": {
                        "cairo_type": "felt*",
                        "offset": 4
                    },
                    "signature_len": {
                        "cairo_type": "felt",
                        "offset": 3
                    },
                    "transaction_hash": {
                        "cairo_type": "felt",
                        "offset": 5
                    },
                    "version": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 8,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.storage_read": {
                "decorators": [],
                "pc": 4,
                "type": "function"
            },
            "starkware.starknet.common.syscalls.storage_read.Args": {
                "full_name": "starkware.starknet.common.syscalls.storage_read.Args",
                "members": {
                    "address": {
                        "cairo_type": "felt",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.storage_read.ImplicitArgs": {
                "full_name": "starkware.starknet.common.syscalls.storage_read.ImplicitArgs",
                "members": {
                    "syscall_ptr": {
                        "cairo_type": "felt*",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.storage_read.Return": {
                "cairo_type": "(value: felt)",
                "type": "type_definition"
            },
            "starkware.starknet.common.syscalls.storage_read.SIZEOF_LOCALS": {
                "type": "const",
                "value": 0
            },
            "starkware.starknet.common.syscalls.storage_read.__temp0": {
                "cairo_type": "felt",
                "full_name": "starkware.starknet.common.syscalls.storage_read.__temp0",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 1,
                            "offset": 1
                        },
                        "pc": 6,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "starkware.starknet.common.syscalls.storage_read.address": {
                "cairo_type": "felt",
                "full_name": "starkware.starknet.common.syscalls.storage_read.address",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 1,
                            "offset": 0
                        },
                        "pc": 4,
                        "value": "[cast(fp + (-3), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "starkware.starknet.common.syscalls.storage_read.response": {
                "cairo_type": "starkware.starknet.common.syscalls.StorageReadResponse",
                "full_name": "starkware.starknet.common.syscalls.storage_read.response",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 1,
                            "offset": 1
                        },
                        "pc": 8,
                        "value": "[cast([fp + (-4)] + 2, starkware.starknet.common.syscalls.StorageReadResponse*)]"
                    }
                ],
                "type": "reference"
            },
            "starkware.starknet.common.syscalls.storage_read.syscall": {
                "cairo_type": "starkware.starknet.common.syscalls.StorageRead",
                "full_name": "starkware.starknet.common.syscalls.storage_read.syscall",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 1,
                            "offset": 0
                        },
                        "pc": 4,
                        "value": "[cast([fp + (-4)], starkware.starknet.common.syscalls.StorageRead*)]"
                    }
                ],
                "type": "reference"
            },
            "starkware.starknet.common.syscalls.storage_read.syscall_ptr": {
                "cairo_type": "felt*",
                "full_name": "starkware.starknet.common.syscalls.storage_read.syscall_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 1,
                            "offset": 0
                        },
                        "pc": 4,
                        "value": "[cast(fp + (-4), felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 1,
                            "offset": 1
                        },
                        "pc": 8,
                        "value": "cast([fp + (-4)] + 3, felt*)"
                    }
                ],
                "type": "reference"
            },
            "starkware.starknet.common.syscalls.storage_write": {
                "decorators": [],
                "pc": 12,
                "type": "function"
            },
            "starkware.starknet.common.syscalls.storage_write.Args": {
                "full_name": "starkware.starknet.common.syscalls.storage_write.Args",
                "members": {
                    "address": {
                        "cairo_type": "felt",
                        "offset": 0
                    },
                    "value": {
                        "cairo_type": "felt",
                        "offset": 1
                    }
                },
                "size": 2,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.storage_write.ImplicitArgs": {
                "full_name": "starkware.starknet.common.syscalls.storage_write.ImplicitArgs",
                "members": {
                    "syscall_ptr": {
                        "cairo_type": "felt*",
                        "offset": 0
                    }
                },
                "size": 1,
                "type": "struct"
            },
            "starkware.starknet.common.syscalls.storage_write.Return": {
                "cairo_type": "()",
                "type": "type_definition"
            },
            "starkware.starknet.common.syscalls.storage_write.SIZEOF_LOCALS": {
                "type": "const",
                "value": 0
            },
            "starkware.starknet.common.syscalls.storage_write.__temp1": {
                "cairo_type": "felt",
                "full_name": "starkware.starknet.common.syscalls.storage_write.__temp1",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 2,
                            "offset": 1
                        },
                        "pc": 14,
                        "value": "[cast(ap + (-1), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "starkware.starknet.common.syscalls.storage_write.address": {
                "cairo_type": "felt",
                "full_name": "starkware.starknet.common.syscalls.storage_write.address",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 2,
                            "offset": 0
                        },
                        "pc": 12,
                        "value": "[cast(fp + (-4), felt*)]"
                    }
                ],
                "type": "reference"
            },
            "starkware.starknet.common.syscalls.storage_write.syscall_ptr": {
                "cairo_type": "felt*",
                "full_name": "starkware.starknet.common.syscalls.storage_write.syscall_ptr",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 2,
                            "offset": 0
                        },
                        "pc": 12,
                        "value": "[cast(fp + (-5), felt**)]"
                    },
                    {
                        "ap_tracking_data": {
                            "group": 2,
                            "offset": 1
                        },
                        "pc": 17,
                        "value": "cast([fp + (-5)] + 3, felt*)"
                    }
                ],
                "type": "reference"
            },
            "starkware.starknet.common.syscalls.storage_write.value": {
                "cairo_type": "felt",
                "full_name": "starkware.starknet.common.syscalls.storage_write.value",
                "references": [
                    {
                        "ap_tracking_data": {
                            "group": 2,
                            "offset": 0
                        },
                        "pc": 12,
                        "value": "[cast(fp + (-3), felt*)]"
                    }
                ],
                "type": "reference"
            }
        },
        "main_scope": "__main__",
        "prime": "0x800000000000011000000000000000000000000000000000000000000000001",
        "reference_manager": {
            "references": [
                {
                    "ap_tracking_data": {
                        "group": 0,
                        "offset": 0
                    },
                    "pc": 0,
                    "value": "[cast(fp + (-3), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 0,
                        "offset": 0
                    },
                    "pc": 0,
                    "value": "[cast(fp + (-4), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 0,
                        "offset": 0
                    },
                    "pc": 1,
                    "value": "cast([fp + (-4)] + 1, felt)"
                },
                {
                    "ap_tracking_data": {
                        "group": 1,
                        "offset": 0
                    },
                    "pc": 4,
                    "value": "[cast(fp + (-3), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 1,
                        "offset": 0
                    },
                    "pc": 4,
                    "value": "[cast(fp + (-4), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 1,
                        "offset": 0
                    },
                    "pc": 4,
                    "value": "[cast([fp + (-4)], starkware.starknet.common.syscalls.StorageRead*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 1,
                        "offset": 1
                    },
                    "pc": 6,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 1,
                        "offset": 1
                    },
                    "pc": 8,
                    "value": "[cast([fp + (-4)] + 2, starkware.starknet.common.syscalls.StorageReadResponse*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 1,
                        "offset": 1
                    },
                    "pc": 8,
                    "value": "cast([fp + (-4)] + 3, felt*)"
                },
                {
                    "ap_tracking_data": {
                        "group": 2,
                        "offset": 0
                    },
                    "pc": 12,
                    "value": "[cast(fp + (-4), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 2,
                        "offset": 0
                    },
                    "pc": 12,
                    "value": "[cast(fp + (-3), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 2,
                        "offset": 0
                    },
                    "pc": 12,
                    "value": "[cast(fp + (-5), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 2,
                        "offset": 1
                    },
                    "pc": 14,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 2,
                        "offset": 1
                    },
                    "pc": 17,
                    "value": "cast([fp + (-5)] + 3, felt*)"
                },
                {
                    "ap_tracking_data": {
                        "group": 3,
                        "offset": 0
                    },
                    "pc": 20,
                    "value": "[cast(fp + (-4), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 3,
                        "offset": 0
                    },
                    "pc": 20,
                    "value": "[cast(fp + (-3), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 3,
                        "offset": 0
                    },
                    "pc": 20,
                    "value": "cast(916907772491729262376534102982219947830828984996257231353398618781993312401, felt)"
                },
                {
                    "ap_tracking_data": {
                        "group": 4,
                        "offset": 0
                    },
                    "pc": 25,
                    "value": "[cast(fp + (-5), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 4,
                        "offset": 0
                    },
                    "pc": 25,
                    "value": "[cast(fp + (-4), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 4,
                        "offset": 0
                    },
                    "pc": 25,
                    "value": "[cast(fp + (-3), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 4,
                        "offset": 7
                    },
                    "pc": 29,
                    "value": "[cast(ap + (-3), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 4,
                        "offset": 7
                    },
                    "pc": 29,
                    "value": "[cast(ap + (-2), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 4,
                        "offset": 7
                    },
                    "pc": 29,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 4,
                        "offset": 14
                    },
                    "pc": 33,
                    "value": "[cast(ap + (-2), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 4,
                        "offset": 14
                    },
                    "pc": 33,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 4,
                        "offset": 15
                    },
                    "pc": 34,
                    "value": "[cast(ap + (-1), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 4,
                        "offset": 16
                    },
                    "pc": 35,
                    "value": "[cast(ap + (-1), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 4,
                        "offset": 17
                    },
                    "pc": 36,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 4,
                        "offset": 18
                    },
                    "pc": 37,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 5,
                        "offset": 0
                    },
                    "pc": 38,
                    "value": "[cast(fp + (-3), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 5,
                        "offset": 0
                    },
                    "pc": 38,
                    "value": "[cast(fp + (-6), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 5,
                        "offset": 0
                    },
                    "pc": 38,
                    "value": "[cast(fp + (-5), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 5,
                        "offset": 0
                    },
                    "pc": 38,
                    "value": "[cast(fp + (-4), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 5,
                        "offset": 7
                    },
                    "pc": 42,
                    "value": "[cast(ap + (-3), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 5,
                        "offset": 7
                    },
                    "pc": 42,
                    "value": "[cast(ap + (-2), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 5,
                        "offset": 7
                    },
                    "pc": 42,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 5,
                        "offset": 14
                    },
                    "pc": 47,
                    "value": "[cast(ap + (-1), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 6,
                        "offset": 0
                    },
                    "pc": 50,
                    "value": "[cast(fp + (-3), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 6,
                        "offset": 0
                    },
                    "pc": 50,
                    "value": "[cast(fp + (-6), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 6,
                        "offset": 0
                    },
                    "pc": 50,
                    "value": "[cast(fp + (-5), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 6,
                        "offset": 0
                    },
                    "pc": 50,
                    "value": "[cast(fp + (-4), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 6,
                        "offset": 5
                    },
                    "pc": 54,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 6,
                        "offset": 28
                    },
                    "pc": 59,
                    "value": "[cast(ap + (-4), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 6,
                        "offset": 28
                    },
                    "pc": 59,
                    "value": "[cast(ap + (-3), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 6,
                        "offset": 28
                    },
                    "pc": 59,
                    "value": "[cast(ap + (-2), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 6,
                        "offset": 28
                    },
                    "pc": 59,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 6,
                        "offset": 50
                    },
                    "pc": 65,
                    "value": "[cast(ap + (-3), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 6,
                        "offset": 50
                    },
                    "pc": 65,
                    "value": "[cast(ap + (-2), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 6,
                        "offset": 50
                    },
                    "pc": 65,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 0
                    },
                    "pc": 66,
                    "value": "[cast([fp + (-5)], felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 0
                    },
                    "pc": 66,
                    "value": "[cast([fp + (-5)] + 1, starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 0
                    },
                    "pc": 66,
                    "value": "[cast([fp + (-5)] + 2, felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 0
                    },
                    "pc": 66,
                    "value": "[cast(fp + (-3), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 0
                    },
                    "pc": 66,
                    "value": "[cast([fp + (-3)], felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 0
                    },
                    "pc": 66,
                    "value": "cast([fp + (-3)] + 1, felt*)"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 0
                    },
                    "pc": 66,
                    "value": "cast([fp + (-3)] + 1 - [fp + (-3)], felt)"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 1
                    },
                    "pc": 68,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 57
                    },
                    "pc": 75,
                    "value": "[cast(ap + (-3), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 57
                    },
                    "pc": 75,
                    "value": "[cast(ap + (-2), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 57
                    },
                    "pc": 75,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 57
                    },
                    "pc": 75,
                    "value": "[cast(ap + 0, ()*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 58
                    },
                    "pc": 77,
                    "value": "[cast(ap + (-1), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 7,
                        "offset": 58
                    },
                    "pc": 77,
                    "value": "cast(0, felt)"
                },
                {
                    "ap_tracking_data": {
                        "group": 8,
                        "offset": 0
                    },
                    "pc": 84,
                    "value": "[cast(fp + (-5), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 8,
                        "offset": 0
                    },
                    "pc": 84,
                    "value": "[cast(fp + (-4), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 8,
                        "offset": 0
                    },
                    "pc": 84,
                    "value": "[cast(fp + (-3), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 8,
                        "offset": 23
                    },
                    "pc": 89,
                    "value": "[cast(ap + (-4), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 8,
                        "offset": 23
                    },
                    "pc": 89,
                    "value": "[cast(ap + (-3), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 8,
                        "offset": 23
                    },
                    "pc": 89,
                    "value": "[cast(ap + (-2), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 8,
                        "offset": 23
                    },
                    "pc": 89,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 9,
                        "offset": 0
                    },
                    "pc": 90,
                    "value": "[cast(fp + (-4), (res: felt)*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 9,
                        "offset": 0
                    },
                    "pc": 90,
                    "value": "[cast(fp + (-3), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 9,
                        "offset": 1
                    },
                    "pc": 92,
                    "value": "[cast(fp, felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 9,
                        "offset": 1
                    },
                    "pc": 92,
                    "value": "[cast(fp, felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 9,
                        "offset": 1
                    },
                    "pc": 93,
                    "value": "cast([fp] + 1, felt*)"
                },
                {
                    "ap_tracking_data": {
                        "group": 9,
                        "offset": 2
                    },
                    "pc": 95,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 10,
                        "offset": 0
                    },
                    "pc": 99,
                    "value": "[cast([fp + (-5)], felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 10,
                        "offset": 0
                    },
                    "pc": 99,
                    "value": "[cast([fp + (-5)] + 1, starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 10,
                        "offset": 0
                    },
                    "pc": 99,
                    "value": "[cast([fp + (-5)] + 2, felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 10,
                        "offset": 0
                    },
                    "pc": 99,
                    "value": "[cast(fp + (-3), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 10,
                        "offset": 0
                    },
                    "pc": 99,
                    "value": "cast([fp + (-3)] - [fp + (-3)], felt)"
                },
                {
                    "ap_tracking_data": {
                        "group": 10,
                        "offset": 28
                    },
                    "pc": 105,
                    "value": "[cast(ap + (-4), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 10,
                        "offset": 28
                    },
                    "pc": 105,
                    "value": "[cast(ap + (-3), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 10,
                        "offset": 28
                    },
                    "pc": 105,
                    "value": "[cast(ap + (-2), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 10,
                        "offset": 28
                    },
                    "pc": 105,
                    "value": "[cast(ap + (-1), (res: felt)*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 10,
                        "offset": 36
                    },
                    "pc": 108,
                    "value": "[cast(ap + (-3), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 10,
                        "offset": 36
                    },
                    "pc": 108,
                    "value": "[cast(ap + (-2), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 10,
                        "offset": 36
                    },
                    "pc": 108,
                    "value": "[cast(ap + (-1), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 11,
                        "offset": 0
                    },
                    "pc": 114,
                    "value": "[cast(fp + (-5), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 11,
                        "offset": 0
                    },
                    "pc": 114,
                    "value": "[cast(fp + (-4), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 11,
                        "offset": 0
                    },
                    "pc": 114,
                    "value": "[cast(fp + (-3), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 11,
                        "offset": 22
                    },
                    "pc": 121,
                    "value": "[cast(ap + (-3), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 11,
                        "offset": 22
                    },
                    "pc": 121,
                    "value": "[cast(ap + (-2), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 11,
                        "offset": 22
                    },
                    "pc": 121,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 12,
                        "offset": 0
                    },
                    "pc": 122,
                    "value": "[cast([fp + (-5)], felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 12,
                        "offset": 0
                    },
                    "pc": 122,
                    "value": "[cast([fp + (-5)] + 1, starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 12,
                        "offset": 0
                    },
                    "pc": 122,
                    "value": "[cast([fp + (-5)] + 2, felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 12,
                        "offset": 0
                    },
                    "pc": 122,
                    "value": "[cast(fp + (-3), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 12,
                        "offset": 0
                    },
                    "pc": 122,
                    "value": "cast([fp + (-3)] - [fp + (-3)], felt)"
                },
                {
                    "ap_tracking_data": {
                        "group": 12,
                        "offset": 27
                    },
                    "pc": 128,
                    "value": "[cast(ap + (-3), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 12,
                        "offset": 27
                    },
                    "pc": 128,
                    "value": "[cast(ap + (-2), starkware.cairo.common.cairo_builtins.HashBuiltin**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 12,
                        "offset": 27
                    },
                    "pc": 128,
                    "value": "[cast(ap + (-1), felt*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 12,
                        "offset": 27
                    },
                    "pc": 128,
                    "value": "[cast(ap + 0, ()*)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 12,
                        "offset": 28
                    },
                    "pc": 130,
                    "value": "[cast(ap + (-1), felt**)]"
                },
                {
                    "ap_tracking_data": {
                        "group": 12,
                        "offset": 28
                    },
                    "pc": 130,
                    "value": "cast(0, felt)"
                }
            ]
        }
    }
}

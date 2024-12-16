# Staked USDe

## Contract Information
- **Contract Name:** StakedUSDeV2
- **Compiler Version:** v0.8.19+commit.7dd6d404
- **Optimization Enabled:** Yes with 20000 runs
- **Contract Address:** 0x9D39A5DE30e57443BfF2A8307A4256c8797A3497
- **EVM Version:** paris
- **Chain:** Ethereum Mainnet
- **Creator:** 0x8de54b1cefedeab1766b947c7d9a9963436e8fae
- **Creation Transaction:** 0x9b099ba3c8e64ea8904cc6de83f2245e309e0f91c3ce1f976328b601e4dda314

## Source Code Structure
```
└── contracts
    ├── StakedUSDeV2.sol
    ├── StakedUSDe.sol
    ├── interfaces
    │   ├── IStakedUSDeCooldown.sol
    │   ├── IStakedUSDe.sol
    │   ├── IUSDeSiloDefinitions.sol
    │   ├── ISingleAdminAccessControl.sol
    ├── USDeSilo.sol
    ├── SingleAdminAccessControl.sol
└── lib
    └── openzeppelin-contracts
        └── contracts
            └── token
                ├── ERC20
                │   └── extensions
                │       ├── ERC4626.sol
                │       ├── ERC20Permit.sol
                │       ├── IERC20Permit.sol
                │       ├── IERC20Metadata.sol
                │   └── utils
                │       ├── SafeERC20.sol
                │   └── IERC20.sol
                │   └── ERC20.sol
            └── security
                ├── ReentrancyGuard.sol
            └── interfaces
                ├── IERC4626.sol
                ├── IERC5313.sol
                ├── IERC5267.sol
            └── utils
                ├── math
                │   ├── Math.sol
                │   ├── SignedMath.sol
                ├── Address.sol
                ├── cryptography
                │   ├── ECDSA.sol
                │   ├── EIP712.sol
                ├── Counters.sol
                ├── Context.sol
                ├── Strings.sol
                ├── ShortStrings.sol
                ├── introspection
                │   ├── ERC165.sol
                │   ├── IERC165.sol
                ├── StorageSlot.sol
            └── access
                └── AccessControl.sol
                └── IAccessControl.sol

```
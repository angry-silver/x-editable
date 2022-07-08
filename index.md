# Solidity API

## Lock

You can use this contract for only the most basic simulation

_All function calls are currently implemented without side effects_

### unlockTime

```solidity
uint256 unlockTime
```

_unlocking time as timestamp_

### owner

```solidity
address payable owner
```

_owner address_

### Withdrawal

```solidity
event Withdrawal(uint256 amount, uint256 when)
```

### constructor

```solidity
constructor(uint256 _unlockTime) public payable
```

### withdraw

```solidity
function withdraw() public
```

Withdraw only when unlocked

_Angry Silver  Only owner can withdraw_

## Lock

### unlockTime

```solidity
uint256 unlockTime
```

### owner

```solidity
address payable owner
```

### Withdrawal

```solidity
event Withdrawal(uint256 amount, uint256 when)
```

### constructor

```solidity
constructor(uint256 _unlockTime) public payable
```

### withdraw

```solidity
function withdraw() public
```


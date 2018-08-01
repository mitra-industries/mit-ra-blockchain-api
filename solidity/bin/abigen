// Code generated - DO NOT EDIT.
// This file is a generated binding and any manual changes will be lost.

package mit-ra_exchange

import (
	"math/big"
	"strings"
)

// AdamCoefficientsABI is the input ABI used to generate the binding from.
const AdamCoefficientsABI = "[{\"constant\":true,\"inputs\":[],\"name\":\"systemOwner\",\"outputs\":[{\"name\":\"\",\"type\":\"address\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"systemOwnerAddress\",\"type\":\"address\"}],\"name\":\"setSystemOwner\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"coeffs\",\"type\":\"int64[]\"}],\"name\":\"setCoefficients\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[{\"name\":\"\",\"type\":\"bytes16\"},{\"name\":\"\",\"type\":\"uint16\"}],\"name\":\"coefficients\",\"outputs\":[{\"name\":\"\",\"type\":\"int64\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"inputs\":[{\"name\":\"systemOwnerAddress\",\"type\":\"address\"}],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"constructor\"}]"

// AdamCoefficientsBin is the compiled bytecode used for deploying new contracts.
const AdamCoefficientsBin = `0x608060405234801561001057600080fd5b5060405160208061045f833981016040525160018054600160a060020a031916600160a060020a0390921691909117905561040f806100506000396000f3006080604052600436106100615763ffffffff7c0100000000000000000000000000000000000000000000000000000000600035041663337792548114610066578063621eb9a2146100a457806383a4c9c3146100d4578063bd40db2d14610141575b600080fd5b34801561007257600080fd5b5061007b61018c565b6040805173ffffffffffffffffffffffffffffffffffffffff9092168252519081900360200190f35b3480156100b057600080fd5b506100d273ffffffffffffffffffffffffffffffffffffffff600435166101a8565b005b3480156100e057600080fd5b506040805160206004602480358281013584810280870186019097528086526100d29684356fffffffffffffffffffffffffffffffff1916963696604495919490910192918291850190849080828437509497506102909650505050505050565b34801561014d57600080fd5b506101736fffffffffffffffffffffffffffffffff196004351661ffff602435166103c6565b60408051600792830b90920b8252519081900360200190f35b60015473ffffffffffffffffffffffffffffffffffffffff1681565b600154604080517f2f54bf6e00000000000000000000000000000000000000000000000000000000815273ffffffffffffffffffffffffffffffffffffffff338116600483015291519190921691632f54bf6e9160248083019260209291908290030181600087803b15801561021d57600080fd5b505af1158015610231573d6000803e3d6000fd5b505050506040513d602081101561024757600080fd5b5051151561025457600080fd5b6001805473ffffffffffffffffffffffffffffffffffffffff191673ffffffffffffffffffffffffffffffffffffffff92909216919091179055565b600154604080517f2f54bf6e00000000000000000000000000000000000000000000000000000000815273ffffffffffffffffffffffffffffffffffffffff338116600483015291516000939290921691632f54bf6e9160248082019260209290919082900301818787803b15801561030857600080fd5b505af115801561031c573d6000803e3d6000fd5b505050506040513d602081101561033257600080fd5b5051151561033f57600080fd5b5060005b81518110156103c157818181518110151561035a57fe5b60209081029091018101516fffffffffffffffffffffffffffffffff1985166000908152808352604080822061ffff8616835290935291909120805460079290920b67ffffffffffffffff1667ffffffffffffffff19909216919091179055600101610343565b505050565b600060208181529281526040808220909352908152205460070b815600a165627a7a7230582055073353cc55371559b369c7ee3dcaaa10d147e68f9349d1707db7c3d2c5230a0029`

// DeployAdamCoefficients deploys a new Ethereum contract, binding an instance of AdamCoefficients to it.
func DeployAdamCoefficients(auth *bind.TransactOpts, backend bind.ContractBackend, systemOwnerAddress common.Address) (common.Address, *types.Transaction, *AdamCoefficients, error) {
	parsed, err := abi.JSON(strings.NewReader(AdamCoefficientsABI))
	if err != nil {
		return common.Address{}, nil, nil, err
	}
	address, tx, contract, err := bind.DeployContract(auth, parsed, common.FromHex(AdamCoefficientsBin), backend, systemOwnerAddress)
	if err != nil {
		return common.Address{}, nil, nil, err
	}
	return address, tx, &AdamCoefficients{AdamCoefficientsCaller: AdamCoefficientsCaller{contract: contract}, AdamCoefficientsTransactor: AdamCoefficientsTransactor{contract: contract}, AdamCoefficientsFilterer: AdamCoefficientsFilterer{contract: contract}}, nil
}

// AdamCoefficients is an auto generated Go binding around an Ethereum contract.
type AdamCoefficients struct {
	AdamCoefficientsCaller     // Read-only binding to the contract
	AdamCoefficientsTransactor // Write-only binding to the contract
	AdamCoefficientsFilterer   // Log filterer for contract events
}

// AdamCoefficientsCaller is an auto generated read-only Go binding around an Ethereum contract.
type AdamCoefficientsCaller struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// AdamCoefficientsTransactor is an auto generated write-only Go binding around an Ethereum contract.
type AdamCoefficientsTransactor struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// AdamCoefficientsFilterer is an auto generated log filtering Go binding around an Ethereum contract events.
type AdamCoefficientsFilterer struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// AdamCoefficientsSession is an auto generated Go binding around an Ethereum contract,
// with pre-set call and transact options.
type AdamCoefficientsSession struct {
	Contract     *AdamCoefficients // Generic contract binding to set the session for
	CallOpts     bind.CallOpts     // Call options to use throughout this session
	TransactOpts bind.TransactOpts // Transaction auth options to use throughout this session
}

// AdamCoefficientsCallerSession is an auto generated read-only Go binding around an Ethereum contract,
// with pre-set call options.
type AdamCoefficientsCallerSession struct {
	Contract *AdamCoefficientsCaller // Generic contract caller binding to set the session for
	CallOpts bind.CallOpts           // Call options to use throughout this session
}

// AdamCoefficientsTransactorSession is an auto generated write-only Go binding around an Ethereum contract,
// with pre-set transact options.
type AdamCoefficientsTransactorSession struct {
	Contract     *AdamCoefficientsTransactor // Generic contract transactor binding to set the session for
	TransactOpts bind.TransactOpts           // Transaction auth options to use throughout this session
}

// AdamCoefficientsRaw is an auto generated low-level Go binding around an Ethereum contract.
type AdamCoefficientsRaw struct {
	Contract *AdamCoefficients // Generic contract binding to access the raw methods on
}

// AdamCoefficientsCallerRaw is an auto generated low-level read-only Go binding around an Ethereum contract.
type AdamCoefficientsCallerRaw struct {
	Contract *AdamCoefficientsCaller // Generic read-only contract binding to access the raw methods on
}

// AdamCoefficientsTransactorRaw is an auto generated low-level write-only Go binding around an Ethereum contract.
type AdamCoefficientsTransactorRaw struct {
	Contract *AdamCoefficientsTransactor // Generic write-only contract binding to access the raw methods on
}

// NewAdamCoefficients creates a new instance of AdamCoefficients, bound to a specific deployed contract.
func NewAdamCoefficients(address common.Address, backend bind.ContractBackend) (*AdamCoefficients, error) {
	contract, err := bindAdamCoefficients(address, backend, backend, backend)
	if err != nil {
		return nil, err
	}
	return &AdamCoefficients{AdamCoefficientsCaller: AdamCoefficientsCaller{contract: contract}, AdamCoefficientsTransactor: AdamCoefficientsTransactor{contract: contract}, AdamCoefficientsFilterer: AdamCoefficientsFilterer{contract: contract}}, nil
}

// NewAdamCoefficientsCaller creates a new read-only instance of AdamCoefficients, bound to a specific deployed contract.
func NewAdamCoefficientsCaller(address common.Address, caller bind.ContractCaller) (*AdamCoefficientsCaller, error) {
	contract, err := bindAdamCoefficients(address, caller, nil, nil)
	if err != nil {
		return nil, err
	}
	return &AdamCoefficientsCaller{contract: contract}, nil
}

// NewAdamCoefficientsTransactor creates a new write-only instance of AdamCoefficients, bound to a specific deployed contract.
func NewAdamCoefficientsTransactor(address common.Address, transactor bind.ContractTransactor) (*AdamCoefficientsTransactor, error) {
	contract, err := bindAdamCoefficients(address, nil, transactor, nil)
	if err != nil {
		return nil, err
	}
	return &AdamCoefficientsTransactor{contract: contract}, nil
}

// NewAdamCoefficientsFilterer creates a new log filterer instance of AdamCoefficients, bound to a specific deployed contract.
func NewAdamCoefficientsFilterer(address common.Address, filterer bind.ContractFilterer) (*AdamCoefficientsFilterer, error) {
	contract, err := bindAdamCoefficients(address, nil, nil, filterer)
	if err != nil {
		return nil, err
	}
	return &AdamCoefficientsFilterer{contract: contract}, nil
}

// bindAdamCoefficients binds a generic wrapper to an already deployed contract.
func bindAdamCoefficients(address common.Address, caller bind.ContractCaller, transactor bind.ContractTransactor, filterer bind.ContractFilterer) (*bind.BoundContract, error) {
	parsed, err := abi.JSON(strings.NewReader(AdamCoefficientsABI))
	if err != nil {
		return nil, err
	}
	return bind.NewBoundContract(address, parsed, caller, transactor, filterer), nil
}

// Call invokes the (constant) contract method with params as input values and
// sets the output to result. The result type might be a single field for simple
// returns, a slice of interfaces for anonymous returns and a struct for named
// returns.
func (_AdamCoefficients *AdamCoefficientsRaw) Call(opts *bind.CallOpts, result interface{}, method string, params ...interface{}) error {
	return _AdamCoefficients.Contract.AdamCoefficientsCaller.contract.Call(opts, result, method, params...)
}

// Transfer initiates a plain transaction to move funds to the contract, calling
// its default method if one is available.
func (_AdamCoefficients *AdamCoefficientsRaw) Transfer(opts *bind.TransactOpts) (*types.Transaction, error) {
	return _AdamCoefficients.Contract.AdamCoefficientsTransactor.contract.Transfer(opts)
}

// Transact invokes the (paid) contract method with params as input values.
func (_AdamCoefficients *AdamCoefficientsRaw) Transact(opts *bind.TransactOpts, method string, params ...interface{}) (*types.Transaction, error) {
	return _AdamCoefficients.Contract.AdamCoefficientsTransactor.contract.Transact(opts, method, params...)
}

// Call invokes the (constant) contract method with params as input values and
// sets the output to result. The result type might be a single field for simple
// returns, a slice of interfaces for anonymous returns and a struct for named
// returns.
func (_AdamCoefficients *AdamCoefficientsCallerRaw) Call(opts *bind.CallOpts, result interface{}, method string, params ...interface{}) error {
	return _AdamCoefficients.Contract.contract.Call(opts, result, method, params...)
}

// Transfer initiates a plain transaction to move funds to the contract, calling
// its default method if one is available.
func (_AdamCoefficients *AdamCoefficientsTransactorRaw) Transfer(opts *bind.TransactOpts) (*types.Transaction, error) {
	return _AdamCoefficients.Contract.contract.Transfer(opts)
}

// Transact invokes the (paid) contract method with params as input values.
func (_AdamCoefficients *AdamCoefficientsTransactorRaw) Transact(opts *bind.TransactOpts, method string, params ...interface{}) (*types.Transaction, error) {
	return _AdamCoefficients.Contract.contract.Transact(opts, method, params...)
}

// Coefficients is a free data retrieval call binding the contract method 0xbd40db2d.
//
// Solidity: function coefficients( bytes16,  uint16) constant returns(int64)
func (_AdamCoefficients *AdamCoefficientsCaller) Coefficients(opts *bind.CallOpts, arg0 [16]byte, arg1 uint16) (int64, error) {
	var (
		ret0 = new(int64)
	)
	out := ret0
	err := _AdamCoefficients.contract.Call(opts, out, "coefficients", arg0, arg1)
	return *ret0, err
}

// Coefficients is a free data retrieval call binding the contract method 0xbd40db2d.
//
// Solidity: function coefficients( bytes16,  uint16) constant returns(int64)
func (_AdamCoefficients *AdamCoefficientsSession) Coefficients(arg0 [16]byte, arg1 uint16) (int64, error) {
	return _AdamCoefficients.Contract.Coefficients(&_AdamCoefficients.CallOpts, arg0, arg1)
}

// Coefficients is a free data retrieval call binding the contract method 0xbd40db2d.
//
// Solidity: function coefficients( bytes16,  uint16) constant returns(int64)
func (_AdamCoefficients *AdamCoefficientsCallerSession) Coefficients(arg0 [16]byte, arg1 uint16) (int64, error) {
	return _AdamCoefficients.Contract.Coefficients(&_AdamCoefficients.CallOpts, arg0, arg1)
}

// SystemOwner is a free data retrieval call binding the contract method 0x33779254.
//
// Solidity: function systemOwner() constant returns(address)
func (_AdamCoefficients *AdamCoefficientsCaller) SystemOwner(opts *bind.CallOpts) (common.Address, error) {
	var (
		ret0 = new(common.Address)
	)
	out := ret0
	err := _AdamCoefficients.contract.Call(opts, out, "systemOwner")
	return *ret0, err
}

// SystemOwner is a free data retrieval call binding the contract method 0x33779254.
//
// Solidity: function systemOwner() constant returns(address)
func (_AdamCoefficients *AdamCoefficientsSession) SystemOwner() (common.Address, error) {
	return _AdamCoefficients.Contract.SystemOwner(&_AdamCoefficients.CallOpts)
}

// SystemOwner is a free data retrieval call binding the contract method 0x33779254.
//
// Solidity: function systemOwner() constant returns(address)
func (_AdamCoefficients *AdamCoefficientsCallerSession) SystemOwner() (common.Address, error) {
	return _AdamCoefficients.Contract.SystemOwner(&_AdamCoefficients.CallOpts)
}

// SetCoefficients is a paid mutator transaction binding the contract method 0x83a4c9c3.
//
// Solidity: function setCoefficients(id bytes16, coeffs int64[]) returns()
func (_AdamCoefficients *AdamCoefficientsTransactor) SetCoefficients(opts *bind.TransactOpts, id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _AdamCoefficients.contract.Transact(opts, "setCoefficients", id, coeffs)
}

// SetCoefficients is a paid mutator transaction binding the contract method 0x83a4c9c3.
//
// Solidity: function setCoefficients(id bytes16, coeffs int64[]) returns()
func (_AdamCoefficients *AdamCoefficientsSession) SetCoefficients(id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _AdamCoefficients.Contract.SetCoefficients(&_AdamCoefficients.TransactOpts, id, coeffs)
}

// SetCoefficients is a paid mutator transaction binding the contract method 0x83a4c9c3.
//
// Solidity: function setCoefficients(id bytes16, coeffs int64[]) returns()
func (_AdamCoefficients *AdamCoefficientsTransactorSession) SetCoefficients(id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _AdamCoefficients.Contract.SetCoefficients(&_AdamCoefficients.TransactOpts, id, coeffs)
}

// SetSystemOwner is a paid mutator transaction binding the contract method 0x621eb9a2.
//
// Solidity: function setSystemOwner(systemOwnerAddress address) returns()
func (_AdamCoefficients *AdamCoefficientsTransactor) SetSystemOwner(opts *bind.TransactOpts, systemOwnerAddress common.Address) (*types.Transaction, error) {
	return _AdamCoefficients.contract.Transact(opts, "setSystemOwner", systemOwnerAddress)
}

// SetSystemOwner is a paid mutator transaction binding the contract method 0x621eb9a2.
//
// Solidity: function setSystemOwner(systemOwnerAddress address) returns()
func (_AdamCoefficients *AdamCoefficientsSession) SetSystemOwner(systemOwnerAddress common.Address) (*types.Transaction, error) {
	return _AdamCoefficients.Contract.SetSystemOwner(&_AdamCoefficients.TransactOpts, systemOwnerAddress)
}

// SetSystemOwner is a paid mutator transaction binding the contract method 0x621eb9a2.
//
// Solidity: function setSystemOwner(systemOwnerAddress address) returns()
func (_AdamCoefficients *AdamCoefficientsTransactorSession) SetSystemOwner(systemOwnerAddress common.Address) (*types.Transaction, error) {
	return _AdamCoefficients.Contract.SetSystemOwner(&_AdamCoefficients.TransactOpts, systemOwnerAddress)
}

// OwnableABI is the input ABI used to generate the binding from.
const OwnableABI = "[{\"constant\":true,\"inputs\":[],\"name\":\"owner\",\"outputs\":[{\"name\":\"\",\"type\":\"address\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"newOwner\",\"type\":\"address\"}],\"name\":\"transferOwnership\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"inputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"constructor\"},{\"anonymous\":false,\"inputs\":[{\"indexed\":true,\"name\":\"previousOwner\",\"type\":\"address\"},{\"indexed\":true,\"name\":\"newOwner\",\"type\":\"address\"}],\"name\":\"OwnershipTransferred\",\"type\":\"event\"}]"

// OwnableBin is the compiled bytecode used for deploying new contracts.
const OwnableBin = `0x608060405234801561001057600080fd5b5060008054600160a060020a033316600160a060020a03199091161790556101778061003d6000396000f30060806040526004361061004b5763ffffffff7c01000000000000000000000000000000000000000000000000000000006000350416638da5cb5b8114610050578063f2fde38b14610081575b600080fd5b34801561005c57600080fd5b506100656100a4565b60408051600160a060020a039092168252519081900360200190f35b34801561008d57600080fd5b506100a2600160a060020a03600435166100b3565b005b600054600160a060020a031681565b60005433600160a060020a039081169116146100ce57600080fd5b600160a060020a03811615156100e357600080fd5b60008054604051600160a060020a03808516939216917f8be0079c531659141344cd1fd0a4f28419497f9722a3daafe3b4186f6b6457e091a36000805473ffffffffffffffffffffffffffffffffffffffff1916600160a060020a03929092169190911790555600a165627a7a72305820a9daa9eadc6400094329f5a79bbe07a7b3743bda62b511c3b14994a49faae9950029`

// DeployOwnable deploys a new Ethereum contract, binding an instance of Ownable to it.
func DeployOwnable(auth *bind.TransactOpts, backend bind.ContractBackend) (common.Address, *types.Transaction, *Ownable, error) {
	parsed, err := abi.JSON(strings.NewReader(OwnableABI))
	if err != nil {
		return common.Address{}, nil, nil, err
	}
	address, tx, contract, err := bind.DeployContract(auth, parsed, common.FromHex(OwnableBin), backend)
	if err != nil {
		return common.Address{}, nil, nil, err
	}
	return address, tx, &Ownable{OwnableCaller: OwnableCaller{contract: contract}, OwnableTransactor: OwnableTransactor{contract: contract}, OwnableFilterer: OwnableFilterer{contract: contract}}, nil
}

// Ownable is an auto generated Go binding around an Ethereum contract.
type Ownable struct {
	OwnableCaller     // Read-only binding to the contract
	OwnableTransactor // Write-only binding to the contract
	OwnableFilterer   // Log filterer for contract events
}

// OwnableCaller is an auto generated read-only Go binding around an Ethereum contract.
type OwnableCaller struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// OwnableTransactor is an auto generated write-only Go binding around an Ethereum contract.
type OwnableTransactor struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// OwnableFilterer is an auto generated log filtering Go binding around an Ethereum contract events.
type OwnableFilterer struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// OwnableSession is an auto generated Go binding around an Ethereum contract,
// with pre-set call and transact options.
type OwnableSession struct {
	Contract     *Ownable          // Generic contract binding to set the session for
	CallOpts     bind.CallOpts     // Call options to use throughout this session
	TransactOpts bind.TransactOpts // Transaction auth options to use throughout this session
}

// OwnableCallerSession is an auto generated read-only Go binding around an Ethereum contract,
// with pre-set call options.
type OwnableCallerSession struct {
	Contract *OwnableCaller // Generic contract caller binding to set the session for
	CallOpts bind.CallOpts  // Call options to use throughout this session
}

// OwnableTransactorSession is an auto generated write-only Go binding around an Ethereum contract,
// with pre-set transact options.
type OwnableTransactorSession struct {
	Contract     *OwnableTransactor // Generic contract transactor binding to set the session for
	TransactOpts bind.TransactOpts  // Transaction auth options to use throughout this session
}

// OwnableRaw is an auto generated low-level Go binding around an Ethereum contract.
type OwnableRaw struct {
	Contract *Ownable // Generic contract binding to access the raw methods on
}

// OwnableCallerRaw is an auto generated low-level read-only Go binding around an Ethereum contract.
type OwnableCallerRaw struct {
	Contract *OwnableCaller // Generic read-only contract binding to access the raw methods on
}

// OwnableTransactorRaw is an auto generated low-level write-only Go binding around an Ethereum contract.
type OwnableTransactorRaw struct {
	Contract *OwnableTransactor // Generic write-only contract binding to access the raw methods on
}

// NewOwnable creates a new instance of Ownable, bound to a specific deployed contract.
func NewOwnable(address common.Address, backend bind.ContractBackend) (*Ownable, error) {
	contract, err := bindOwnable(address, backend, backend, backend)
	if err != nil {
		return nil, err
	}
	return &Ownable{OwnableCaller: OwnableCaller{contract: contract}, OwnableTransactor: OwnableTransactor{contract: contract}, OwnableFilterer: OwnableFilterer{contract: contract}}, nil
}

// NewOwnableCaller creates a new read-only instance of Ownable, bound to a specific deployed contract.
func NewOwnableCaller(address common.Address, caller bind.ContractCaller) (*OwnableCaller, error) {
	contract, err := bindOwnable(address, caller, nil, nil)
	if err != nil {
		return nil, err
	}
	return &OwnableCaller{contract: contract}, nil
}

// NewOwnableTransactor creates a new write-only instance of Ownable, bound to a specific deployed contract.
func NewOwnableTransactor(address common.Address, transactor bind.ContractTransactor) (*OwnableTransactor, error) {
	contract, err := bindOwnable(address, nil, transactor, nil)
	if err != nil {
		return nil, err
	}
	return &OwnableTransactor{contract: contract}, nil
}

// NewOwnableFilterer creates a new log filterer instance of Ownable, bound to a specific deployed contract.
func NewOwnableFilterer(address common.Address, filterer bind.ContractFilterer) (*OwnableFilterer, error) {
	contract, err := bindOwnable(address, nil, nil, filterer)
	if err != nil {
		return nil, err
	}
	return &OwnableFilterer{contract: contract}, nil
}

// bindOwnable binds a generic wrapper to an already deployed contract.
func bindOwnable(address common.Address, caller bind.ContractCaller, transactor bind.ContractTransactor, filterer bind.ContractFilterer) (*bind.BoundContract, error) {
	parsed, err := abi.JSON(strings.NewReader(OwnableABI))
	if err != nil {
		return nil, err
	}
	return bind.NewBoundContract(address, parsed, caller, transactor, filterer), nil
}

// Call invokes the (constant) contract method with params as input values and
// sets the output to result. The result type might be a single field for simple
// returns, a slice of interfaces for anonymous returns and a struct for named
// returns.
func (_Ownable *OwnableRaw) Call(opts *bind.CallOpts, result interface{}, method string, params ...interface{}) error {
	return _Ownable.Contract.OwnableCaller.contract.Call(opts, result, method, params...)
}

// Transfer initiates a plain transaction to move funds to the contract, calling
// its default method if one is available.
func (_Ownable *OwnableRaw) Transfer(opts *bind.TransactOpts) (*types.Transaction, error) {
	return _Ownable.Contract.OwnableTransactor.contract.Transfer(opts)
}

// Transact invokes the (paid) contract method with params as input values.
func (_Ownable *OwnableRaw) Transact(opts *bind.TransactOpts, method string, params ...interface{}) (*types.Transaction, error) {
	return _Ownable.Contract.OwnableTransactor.contract.Transact(opts, method, params...)
}

// Call invokes the (constant) contract method with params as input values and
// sets the output to result. The result type might be a single field for simple
// returns, a slice of interfaces for anonymous returns and a struct for named
// returns.
func (_Ownable *OwnableCallerRaw) Call(opts *bind.CallOpts, result interface{}, method string, params ...interface{}) error {
	return _Ownable.Contract.contract.Call(opts, result, method, params...)
}

// Transfer initiates a plain transaction to move funds to the contract, calling
// its default method if one is available.
func (_Ownable *OwnableTransactorRaw) Transfer(opts *bind.TransactOpts) (*types.Transaction, error) {
	return _Ownable.Contract.contract.Transfer(opts)
}

// Transact invokes the (paid) contract method with params as input values.
func (_Ownable *OwnableTransactorRaw) Transact(opts *bind.TransactOpts, method string, params ...interface{}) (*types.Transaction, error) {
	return _Ownable.Contract.contract.Transact(opts, method, params...)
}

// Owner is a free data retrieval call binding the contract method 0x8da5cb5b.
//
// Solidity: function owner() constant returns(address)
func (_Ownable *OwnableCaller) Owner(opts *bind.CallOpts) (common.Address, error) {
	var (
		ret0 = new(common.Address)
	)
	out := ret0
	err := _Ownable.contract.Call(opts, out, "owner")
	return *ret0, err
}

// Owner is a free data retrieval call binding the contract method 0x8da5cb5b.
//
// Solidity: function owner() constant returns(address)
func (_Ownable *OwnableSession) Owner() (common.Address, error) {
	return _Ownable.Contract.Owner(&_Ownable.CallOpts)
}

// Owner is a free data retrieval call binding the contract method 0x8da5cb5b.
//
// Solidity: function owner() constant returns(address)
func (_Ownable *OwnableCallerSession) Owner() (common.Address, error) {
	return _Ownable.Contract.Owner(&_Ownable.CallOpts)
}

// TransferOwnership is a paid mutator transaction binding the contract method 0xf2fde38b.
//
// Solidity: function transferOwnership(newOwner address) returns()
func (_Ownable *OwnableTransactor) TransferOwnership(opts *bind.TransactOpts, newOwner common.Address) (*types.Transaction, error) {
	return _Ownable.contract.Transact(opts, "transferOwnership", newOwner)
}

// TransferOwnership is a paid mutator transaction binding the contract method 0xf2fde38b.
//
// Solidity: function transferOwnership(newOwner address) returns()
func (_Ownable *OwnableSession) TransferOwnership(newOwner common.Address) (*types.Transaction, error) {
	return _Ownable.Contract.TransferOwnership(&_Ownable.TransactOpts, newOwner)
}

// TransferOwnership is a paid mutator transaction binding the contract method 0xf2fde38b.
//
// Solidity: function transferOwnership(newOwner address) returns()
func (_Ownable *OwnableTransactorSession) TransferOwnership(newOwner common.Address) (*types.Transaction, error) {
	return _Ownable.Contract.TransferOwnership(&_Ownable.TransactOpts, newOwner)
}

// OwnableOwnershipTransferredIterator is returned from FilterOwnershipTransferred and is used to iterate over the raw logs and unpacked data for OwnershipTransferred events raised by the Ownable contract.
type OwnableOwnershipTransferredIterator struct {
	Event *OwnableOwnershipTransferred // Event containing the contract specifics and raw log

	contract *bind.BoundContract // Generic contract to use for unpacking event data
	event    string              // Event name to use for unpacking event data

	logs chan types.Log        // Log channel receiving the found contract events
	sub  ethereum.Subscription // Subscription for errors, completion and termination
	done bool                  // Whether the subscription completed delivering logs
	fail error                 // Occurred error to stop iteration
}

// Next advances the iterator to the subsequent event, returning whether there
// are any more events found. In case of a retrieval or parsing error, false is
// returned and Error() can be queried for the exact failure.
func (it *OwnableOwnershipTransferredIterator) Next() bool {
	// If the iterator failed, stop iterating
	if it.fail != nil {
		return false
	}
	// If the iterator completed, deliver directly whatever's available
	if it.done {
		select {
		case log := <-it.logs:
			it.Event = new(OwnableOwnershipTransferred)
			if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
				it.fail = err
				return false
			}
			it.Event.Raw = log
			return true

		default:
			return false
		}
	}
	// Iterator still in progress, wait for either a data or an error event
	select {
	case log := <-it.logs:
		it.Event = new(OwnableOwnershipTransferred)
		if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
			it.fail = err
			return false
		}
		it.Event.Raw = log
		return true

	case err := <-it.sub.Err():
		it.done = true
		it.fail = err
		return it.Next()
	}
}

// Error returns any retrieval or parsing error occurred during filtering.
func (it *OwnableOwnershipTransferredIterator) Error() error {
	return it.fail
}

// Close terminates the iteration process, releasing any pending underlying
// resources.
func (it *OwnableOwnershipTransferredIterator) Close() error {
	it.sub.Unsubscribe()
	return nil
}

// OwnableOwnershipTransferred represents a OwnershipTransferred event raised by the Ownable contract.
type OwnableOwnershipTransferred struct {
	PreviousOwner common.Address
	NewOwner      common.Address
	Raw           types.Log // Blockchain specific contextual infos
}

// FilterOwnershipTransferred is a free log retrieval operation binding the contract event 0x8be0079c531659141344cd1fd0a4f28419497f9722a3daafe3b4186f6b6457e0.
//
// Solidity: event OwnershipTransferred(previousOwner indexed address, newOwner indexed address)
func (_Ownable *OwnableFilterer) FilterOwnershipTransferred(opts *bind.FilterOpts, previousOwner []common.Address, newOwner []common.Address) (*OwnableOwnershipTransferredIterator, error) {

	var previousOwnerRule []interface{}
	for _, previousOwnerItem := range previousOwner {
		previousOwnerRule = append(previousOwnerRule, previousOwnerItem)
	}
	var newOwnerRule []interface{}
	for _, newOwnerItem := range newOwner {
		newOwnerRule = append(newOwnerRule, newOwnerItem)
	}

	logs, sub, err := _Ownable.contract.FilterLogs(opts, "OwnershipTransferred", previousOwnerRule, newOwnerRule)
	if err != nil {
		return nil, err
	}
	return &OwnableOwnershipTransferredIterator{contract: _Ownable.contract, event: "OwnershipTransferred", logs: logs, sub: sub}, nil
}

// WatchOwnershipTransferred is a free log subscription operation binding the contract event 0x8be0079c531659141344cd1fd0a4f28419497f9722a3daafe3b4186f6b6457e0.
//
// Solidity: event OwnershipTransferred(previousOwner indexed address, newOwner indexed address)
func (_Ownable *OwnableFilterer) WatchOwnershipTransferred(opts *bind.WatchOpts, sink chan<- *OwnableOwnershipTransferred, previousOwner []common.Address, newOwner []common.Address) (event.Subscription, error) {

	var previousOwnerRule []interface{}
	for _, previousOwnerItem := range previousOwner {
		previousOwnerRule = append(previousOwnerRule, previousOwnerItem)
	}
	var newOwnerRule []interface{}
	for _, newOwnerItem := range newOwner {
		newOwnerRule = append(newOwnerRule, newOwnerItem)
	}

	logs, sub, err := _Ownable.contract.WatchLogs(opts, "OwnershipTransferred", previousOwnerRule, newOwnerRule)
	if err != nil {
		return nil, err
	}
	return event.NewSubscription(func(quit <-chan struct{}) error {
		defer sub.Unsubscribe()
		for {
			select {
			case log := <-logs:
				// New log arrived, parse the event and forward to the user
				event := new(OwnableOwnershipTransferred)
				if err := _Ownable.contract.UnpackLog(event, "OwnershipTransferred", log); err != nil {
					return err
				}
				event.Raw = log

				select {
				case sink <- event:
				case err := <-sub.Err():
					return err
				case <-quit:
					return nil
				}
			case err := <-sub.Err():
				return err
			case <-quit:
				return nil
			}
		}
	}), nil
}

// SafeMathABI is the input ABI used to generate the binding from.
const SafeMathABI = "[]"

// SafeMathBin is the compiled bytecode used for deploying new contracts.
const SafeMathBin = `0x604c602c600b82828239805160001a60731460008114601c57601e565bfe5b5030600052607381538281f30073000000000000000000000000000000000000000030146080604052600080fd00a165627a7a72305820cb44a8a0a62a134709766fcf940af2b7546623397f5beead5b802d2393550e9f0029`

// DeploySafeMath deploys a new Ethereum contract, binding an instance of SafeMath to it.
func DeploySafeMath(auth *bind.TransactOpts, backend bind.ContractBackend) (common.Address, *types.Transaction, *SafeMath, error) {
	parsed, err := abi.JSON(strings.NewReader(SafeMathABI))
	if err != nil {
		return common.Address{}, nil, nil, err
	}
	address, tx, contract, err := bind.DeployContract(auth, parsed, common.FromHex(SafeMathBin), backend)
	if err != nil {
		return common.Address{}, nil, nil, err
	}
	return address, tx, &SafeMath{SafeMathCaller: SafeMathCaller{contract: contract}, SafeMathTransactor: SafeMathTransactor{contract: contract}, SafeMathFilterer: SafeMathFilterer{contract: contract}}, nil
}

// SafeMath is an auto generated Go binding around an Ethereum contract.
type SafeMath struct {
	SafeMathCaller     // Read-only binding to the contract
	SafeMathTransactor // Write-only binding to the contract
	SafeMathFilterer   // Log filterer for contract events
}

// SafeMathCaller is an auto generated read-only Go binding around an Ethereum contract.
type SafeMathCaller struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// SafeMathTransactor is an auto generated write-only Go binding around an Ethereum contract.
type SafeMathTransactor struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// SafeMathFilterer is an auto generated log filtering Go binding around an Ethereum contract events.
type SafeMathFilterer struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// SafeMathSession is an auto generated Go binding around an Ethereum contract,
// with pre-set call and transact options.
type SafeMathSession struct {
	Contract     *SafeMath         // Generic contract binding to set the session for
	CallOpts     bind.CallOpts     // Call options to use throughout this session
	TransactOpts bind.TransactOpts // Transaction auth options to use throughout this session
}

// SafeMathCallerSession is an auto generated read-only Go binding around an Ethereum contract,
// with pre-set call options.
type SafeMathCallerSession struct {
	Contract *SafeMathCaller // Generic contract caller binding to set the session for
	CallOpts bind.CallOpts   // Call options to use throughout this session
}

// SafeMathTransactorSession is an auto generated write-only Go binding around an Ethereum contract,
// with pre-set transact options.
type SafeMathTransactorSession struct {
	Contract     *SafeMathTransactor // Generic contract transactor binding to set the session for
	TransactOpts bind.TransactOpts   // Transaction auth options to use throughout this session
}

// SafeMathRaw is an auto generated low-level Go binding around an Ethereum contract.
type SafeMathRaw struct {
	Contract *SafeMath // Generic contract binding to access the raw methods on
}

// SafeMathCallerRaw is an auto generated low-level read-only Go binding around an Ethereum contract.
type SafeMathCallerRaw struct {
	Contract *SafeMathCaller // Generic read-only contract binding to access the raw methods on
}

// SafeMathTransactorRaw is an auto generated low-level write-only Go binding around an Ethereum contract.
type SafeMathTransactorRaw struct {
	Contract *SafeMathTransactor // Generic write-only contract binding to access the raw methods on
}

// NewSafeMath creates a new instance of SafeMath, bound to a specific deployed contract.
func NewSafeMath(address common.Address, backend bind.ContractBackend) (*SafeMath, error) {
	contract, err := bindSafeMath(address, backend, backend, backend)
	if err != nil {
		return nil, err
	}
	return &SafeMath{SafeMathCaller: SafeMathCaller{contract: contract}, SafeMathTransactor: SafeMathTransactor{contract: contract}, SafeMathFilterer: SafeMathFilterer{contract: contract}}, nil
}

// NewSafeMathCaller creates a new read-only instance of SafeMath, bound to a specific deployed contract.
func NewSafeMathCaller(address common.Address, caller bind.ContractCaller) (*SafeMathCaller, error) {
	contract, err := bindSafeMath(address, caller, nil, nil)
	if err != nil {
		return nil, err
	}
	return &SafeMathCaller{contract: contract}, nil
}

// NewSafeMathTransactor creates a new write-only instance of SafeMath, bound to a specific deployed contract.
func NewSafeMathTransactor(address common.Address, transactor bind.ContractTransactor) (*SafeMathTransactor, error) {
	contract, err := bindSafeMath(address, nil, transactor, nil)
	if err != nil {
		return nil, err
	}
	return &SafeMathTransactor{contract: contract}, nil
}

// NewSafeMathFilterer creates a new log filterer instance of SafeMath, bound to a specific deployed contract.
func NewSafeMathFilterer(address common.Address, filterer bind.ContractFilterer) (*SafeMathFilterer, error) {
	contract, err := bindSafeMath(address, nil, nil, filterer)
	if err != nil {
		return nil, err
	}
	return &SafeMathFilterer{contract: contract}, nil
}

// bindSafeMath binds a generic wrapper to an already deployed contract.
func bindSafeMath(address common.Address, caller bind.ContractCaller, transactor bind.ContractTransactor, filterer bind.ContractFilterer) (*bind.BoundContract, error) {
	parsed, err := abi.JSON(strings.NewReader(SafeMathABI))
	if err != nil {
		return nil, err
	}
	return bind.NewBoundContract(address, parsed, caller, transactor, filterer), nil
}

// Call invokes the (constant) contract method with params as input values and
// sets the output to result. The result type might be a single field for simple
// returns, a slice of interfaces for anonymous returns and a struct for named
// returns.
func (_SafeMath *SafeMathRaw) Call(opts *bind.CallOpts, result interface{}, method string, params ...interface{}) error {
	return _SafeMath.Contract.SafeMathCaller.contract.Call(opts, result, method, params...)
}

// Transfer initiates a plain transaction to move funds to the contract, calling
// its default method if one is available.
func (_SafeMath *SafeMathRaw) Transfer(opts *bind.TransactOpts) (*types.Transaction, error) {
	return _SafeMath.Contract.SafeMathTransactor.contract.Transfer(opts)
}

// Transact invokes the (paid) contract method with params as input values.
func (_SafeMath *SafeMathRaw) Transact(opts *bind.TransactOpts, method string, params ...interface{}) (*types.Transaction, error) {
	return _SafeMath.Contract.SafeMathTransactor.contract.Transact(opts, method, params...)
}

// Call invokes the (constant) contract method with params as input values and
// sets the output to result. The result type might be a single field for simple
// returns, a slice of interfaces for anonymous returns and a struct for named
// returns.
func (_SafeMath *SafeMathCallerRaw) Call(opts *bind.CallOpts, result interface{}, method string, params ...interface{}) error {
	return _SafeMath.Contract.contract.Call(opts, result, method, params...)
}

// Transfer initiates a plain transaction to move funds to the contract, calling
// its default method if one is available.
func (_SafeMath *SafeMathTransactorRaw) Transfer(opts *bind.TransactOpts) (*types.Transaction, error) {
	return _SafeMath.Contract.contract.Transfer(opts)
}

// Transact invokes the (paid) contract method with params as input values.
func (_SafeMath *SafeMathTransactorRaw) Transact(opts *bind.TransactOpts, method string, params ...interface{}) (*types.Transaction, error) {
	return _SafeMath.Contract.contract.Transact(opts, method, params...)
}

// SystemOwnerABI is the input ABI used to generate the binding from.
const SystemOwnerABI = "[{\"constant\":false,\"inputs\":[{\"name\":\"owner\",\"type\":\"address\"}],\"name\":\"isOwner\",\"outputs\":[{\"name\":\"\",\"type\":\"bool\"}],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"owner\",\"type\":\"address\"}],\"name\":\"addOwner\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"i\",\"type\":\"uint16\"}],\"name\":\"deleteOwner\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[],\"name\":\"owner\",\"outputs\":[{\"name\":\"\",\"type\":\"address\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"i\",\"type\":\"uint16\"},{\"name\":\"owner\",\"type\":\"address\"}],\"name\":\"setOwner\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[{\"name\":\"\",\"type\":\"uint16\"}],\"name\":\"owners\",\"outputs\":[{\"name\":\"\",\"type\":\"address\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"newOwner\",\"type\":\"address\"}],\"name\":\"transferOwnership\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"anonymous\":false,\"inputs\":[{\"indexed\":true,\"name\":\"previousOwner\",\"type\":\"address\"},{\"indexed\":true,\"name\":\"newOwner\",\"type\":\"address\"}],\"name\":\"OwnershipTransferred\",\"type\":\"event\"}]"

// SystemOwnerBin is the compiled bytecode used for deploying new contracts.
const SystemOwnerBin = `0x608060405260008054600160a060020a033316600160a060020a0319909116179055610467806100306000396000f3006080604052600436106100825763ffffffff7c01000000000000000000000000000000000000000000000000000000006000350416632f54bf6e81146100875780637065cb48146100bc5780638d257332146100df5780638da5cb5b146100fb57806395a708631461012c578063c15d25b114610154578063f2fde38b14610170575b600080fd5b34801561009357600080fd5b506100a8600160a060020a0360043516610191565b604080519115158252519081900360200190f35b3480156100c857600080fd5b506100dd600160a060020a036004351661020b565b005b3480156100eb57600080fd5b506100dd61ffff60043516610284565b34801561010757600080fd5b506101106102f6565b60408051600160a060020a039092168252519081900360200190f35b34801561013857600080fd5b506100dd61ffff60043516600160a060020a0360243516610305565b34801561016057600080fd5b5061011061ffff60043516610388565b34801561017c57600080fd5b506100dd600160a060020a03600435166103a3565b60008080600160a060020a03841615156101aa57600080fd5b600091505b60025461ffff90811690831610156101ff575061ffff8116600090815260016020526040902054600160a060020a039081169084168114156101f45760019250610204565b6001909101906101af565b600092505b5050919050565b60005433600160a060020a0390811691161461022657600080fd5b6002805461ffff9081166000908152600160208190526040909120805473ffffffffffffffffffffffffffffffffffffffff1916600160a060020a039590951694909417909355815461ffff19811690821690930116919091179055565b60005433600160a060020a0390811691161461029f57600080fd5b61ffff8116600090815260016020526040902054600160a060020a031615156102c757600080fd5b61ffff166000908152600160205260409020805473ffffffffffffffffffffffffffffffffffffffff19169055565b600054600160a060020a031681565b60005433600160a060020a0390811691161461032057600080fd5b61ffff8216600090815260016020526040902054600160a060020a03161561034757600080fd5b61ffff919091166000908152600160205260409020805473ffffffffffffffffffffffffffffffffffffffff1916600160a060020a03909216919091179055565b600160205260009081526040902054600160a060020a031681565b60005433600160a060020a039081169116146103be57600080fd5b600160a060020a03811615156103d357600080fd5b60008054604051600160a060020a03808516939216917f8be0079c531659141344cd1fd0a4f28419497f9722a3daafe3b4186f6b6457e091a36000805473ffffffffffffffffffffffffffffffffffffffff1916600160a060020a03929092169190911790555600a165627a7a72305820065ad3730de9c97993491483efd46c71ac013c52e3e40d1cdaa2296efbd566f10029`

// DeploySystemOwner deploys a new Ethereum contract, binding an instance of SystemOwner to it.
func DeploySystemOwner(auth *bind.TransactOpts, backend bind.ContractBackend) (common.Address, *types.Transaction, *SystemOwner, error) {
	parsed, err := abi.JSON(strings.NewReader(SystemOwnerABI))
	if err != nil {
		return common.Address{}, nil, nil, err
	}
	address, tx, contract, err := bind.DeployContract(auth, parsed, common.FromHex(SystemOwnerBin), backend)
	if err != nil {
		return common.Address{}, nil, nil, err
	}
	return address, tx, &SystemOwner{SystemOwnerCaller: SystemOwnerCaller{contract: contract}, SystemOwnerTransactor: SystemOwnerTransactor{contract: contract}, SystemOwnerFilterer: SystemOwnerFilterer{contract: contract}}, nil
}

// SystemOwner is an auto generated Go binding around an Ethereum contract.
type SystemOwner struct {
	SystemOwnerCaller     // Read-only binding to the contract
	SystemOwnerTransactor // Write-only binding to the contract
	SystemOwnerFilterer   // Log filterer for contract events
}

// SystemOwnerCaller is an auto generated read-only Go binding around an Ethereum contract.
type SystemOwnerCaller struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// SystemOwnerTransactor is an auto generated write-only Go binding around an Ethereum contract.
type SystemOwnerTransactor struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// SystemOwnerFilterer is an auto generated log filtering Go binding around an Ethereum contract events.
type SystemOwnerFilterer struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// SystemOwnerSession is an auto generated Go binding around an Ethereum contract,
// with pre-set call and transact options.
type SystemOwnerSession struct {
	Contract     *SystemOwner      // Generic contract binding to set the session for
	CallOpts     bind.CallOpts     // Call options to use throughout this session
	TransactOpts bind.TransactOpts // Transaction auth options to use throughout this session
}

// SystemOwnerCallerSession is an auto generated read-only Go binding around an Ethereum contract,
// with pre-set call options.
type SystemOwnerCallerSession struct {
	Contract *SystemOwnerCaller // Generic contract caller binding to set the session for
	CallOpts bind.CallOpts      // Call options to use throughout this session
}

// SystemOwnerTransactorSession is an auto generated write-only Go binding around an Ethereum contract,
// with pre-set transact options.
type SystemOwnerTransactorSession struct {
	Contract     *SystemOwnerTransactor // Generic contract transactor binding to set the session for
	TransactOpts bind.TransactOpts      // Transaction auth options to use throughout this session
}

// SystemOwnerRaw is an auto generated low-level Go binding around an Ethereum contract.
type SystemOwnerRaw struct {
	Contract *SystemOwner // Generic contract binding to access the raw methods on
}

// SystemOwnerCallerRaw is an auto generated low-level read-only Go binding around an Ethereum contract.
type SystemOwnerCallerRaw struct {
	Contract *SystemOwnerCaller // Generic read-only contract binding to access the raw methods on
}

// SystemOwnerTransactorRaw is an auto generated low-level write-only Go binding around an Ethereum contract.
type SystemOwnerTransactorRaw struct {
	Contract *SystemOwnerTransactor // Generic write-only contract binding to access the raw methods on
}

// NewSystemOwner creates a new instance of SystemOwner, bound to a specific deployed contract.
func NewSystemOwner(address common.Address, backend bind.ContractBackend) (*SystemOwner, error) {
	contract, err := bindSystemOwner(address, backend, backend, backend)
	if err != nil {
		return nil, err
	}
	return &SystemOwner{SystemOwnerCaller: SystemOwnerCaller{contract: contract}, SystemOwnerTransactor: SystemOwnerTransactor{contract: contract}, SystemOwnerFilterer: SystemOwnerFilterer{contract: contract}}, nil
}

// NewSystemOwnerCaller creates a new read-only instance of SystemOwner, bound to a specific deployed contract.
func NewSystemOwnerCaller(address common.Address, caller bind.ContractCaller) (*SystemOwnerCaller, error) {
	contract, err := bindSystemOwner(address, caller, nil, nil)
	if err != nil {
		return nil, err
	}
	return &SystemOwnerCaller{contract: contract}, nil
}

// NewSystemOwnerTransactor creates a new write-only instance of SystemOwner, bound to a specific deployed contract.
func NewSystemOwnerTransactor(address common.Address, transactor bind.ContractTransactor) (*SystemOwnerTransactor, error) {
	contract, err := bindSystemOwner(address, nil, transactor, nil)
	if err != nil {
		return nil, err
	}
	return &SystemOwnerTransactor{contract: contract}, nil
}

// NewSystemOwnerFilterer creates a new log filterer instance of SystemOwner, bound to a specific deployed contract.
func NewSystemOwnerFilterer(address common.Address, filterer bind.ContractFilterer) (*SystemOwnerFilterer, error) {
	contract, err := bindSystemOwner(address, nil, nil, filterer)
	if err != nil {
		return nil, err
	}
	return &SystemOwnerFilterer{contract: contract}, nil
}

// bindSystemOwner binds a generic wrapper to an already deployed contract.
func bindSystemOwner(address common.Address, caller bind.ContractCaller, transactor bind.ContractTransactor, filterer bind.ContractFilterer) (*bind.BoundContract, error) {
	parsed, err := abi.JSON(strings.NewReader(SystemOwnerABI))
	if err != nil {
		return nil, err
	}
	return bind.NewBoundContract(address, parsed, caller, transactor, filterer), nil
}

// Call invokes the (constant) contract method with params as input values and
// sets the output to result. The result type might be a single field for simple
// returns, a slice of interfaces for anonymous returns and a struct for named
// returns.
func (_SystemOwner *SystemOwnerRaw) Call(opts *bind.CallOpts, result interface{}, method string, params ...interface{}) error {
	return _SystemOwner.Contract.SystemOwnerCaller.contract.Call(opts, result, method, params...)
}

// Transfer initiates a plain transaction to move funds to the contract, calling
// its default method if one is available.
func (_SystemOwner *SystemOwnerRaw) Transfer(opts *bind.TransactOpts) (*types.Transaction, error) {
	return _SystemOwner.Contract.SystemOwnerTransactor.contract.Transfer(opts)
}

// Transact invokes the (paid) contract method with params as input values.
func (_SystemOwner *SystemOwnerRaw) Transact(opts *bind.TransactOpts, method string, params ...interface{}) (*types.Transaction, error) {
	return _SystemOwner.Contract.SystemOwnerTransactor.contract.Transact(opts, method, params...)
}

// Call invokes the (constant) contract method with params as input values and
// sets the output to result. The result type might be a single field for simple
// returns, a slice of interfaces for anonymous returns and a struct for named
// returns.
func (_SystemOwner *SystemOwnerCallerRaw) Call(opts *bind.CallOpts, result interface{}, method string, params ...interface{}) error {
	return _SystemOwner.Contract.contract.Call(opts, result, method, params...)
}

// Transfer initiates a plain transaction to move funds to the contract, calling
// its default method if one is available.
func (_SystemOwner *SystemOwnerTransactorRaw) Transfer(opts *bind.TransactOpts) (*types.Transaction, error) {
	return _SystemOwner.Contract.contract.Transfer(opts)
}

// Transact invokes the (paid) contract method with params as input values.
func (_SystemOwner *SystemOwnerTransactorRaw) Transact(opts *bind.TransactOpts, method string, params ...interface{}) (*types.Transaction, error) {
	return _SystemOwner.Contract.contract.Transact(opts, method, params...)
}

// Owner is a free data retrieval call binding the contract method 0x8da5cb5b.
//
// Solidity: function owner() constant returns(address)
func (_SystemOwner *SystemOwnerCaller) Owner(opts *bind.CallOpts) (common.Address, error) {
	var (
		ret0 = new(common.Address)
	)
	out := ret0
	err := _SystemOwner.contract.Call(opts, out, "owner")
	return *ret0, err
}

// Owner is a free data retrieval call binding the contract method 0x8da5cb5b.
//
// Solidity: function owner() constant returns(address)
func (_SystemOwner *SystemOwnerSession) Owner() (common.Address, error) {
	return _SystemOwner.Contract.Owner(&_SystemOwner.CallOpts)
}

// Owner is a free data retrieval call binding the contract method 0x8da5cb5b.
//
// Solidity: function owner() constant returns(address)
func (_SystemOwner *SystemOwnerCallerSession) Owner() (common.Address, error) {
	return _SystemOwner.Contract.Owner(&_SystemOwner.CallOpts)
}

// Owners is a free data retrieval call binding the contract method 0xc15d25b1.
//
// Solidity: function owners( uint16) constant returns(address)
func (_SystemOwner *SystemOwnerCaller) Owners(opts *bind.CallOpts, arg0 uint16) (common.Address, error) {
	var (
		ret0 = new(common.Address)
	)
	out := ret0
	err := _SystemOwner.contract.Call(opts, out, "owners", arg0)
	return *ret0, err
}

// Owners is a free data retrieval call binding the contract method 0xc15d25b1.
//
// Solidity: function owners( uint16) constant returns(address)
func (_SystemOwner *SystemOwnerSession) Owners(arg0 uint16) (common.Address, error) {
	return _SystemOwner.Contract.Owners(&_SystemOwner.CallOpts, arg0)
}

// Owners is a free data retrieval call binding the contract method 0xc15d25b1.
//
// Solidity: function owners( uint16) constant returns(address)
func (_SystemOwner *SystemOwnerCallerSession) Owners(arg0 uint16) (common.Address, error) {
	return _SystemOwner.Contract.Owners(&_SystemOwner.CallOpts, arg0)
}

// AddOwner is a paid mutator transaction binding the contract method 0x7065cb48.
//
// Solidity: function addOwner(owner address) returns()
func (_SystemOwner *SystemOwnerTransactor) AddOwner(opts *bind.TransactOpts, owner common.Address) (*types.Transaction, error) {
	return _SystemOwner.contract.Transact(opts, "addOwner", owner)
}

// AddOwner is a paid mutator transaction binding the contract method 0x7065cb48.
//
// Solidity: function addOwner(owner address) returns()
func (_SystemOwner *SystemOwnerSession) AddOwner(owner common.Address) (*types.Transaction, error) {
	return _SystemOwner.Contract.AddOwner(&_SystemOwner.TransactOpts, owner)
}

// AddOwner is a paid mutator transaction binding the contract method 0x7065cb48.
//
// Solidity: function addOwner(owner address) returns()
func (_SystemOwner *SystemOwnerTransactorSession) AddOwner(owner common.Address) (*types.Transaction, error) {
	return _SystemOwner.Contract.AddOwner(&_SystemOwner.TransactOpts, owner)
}

// DeleteOwner is a paid mutator transaction binding the contract method 0x8d257332.
//
// Solidity: function deleteOwner(i uint16) returns()
func (_SystemOwner *SystemOwnerTransactor) DeleteOwner(opts *bind.TransactOpts, i uint16) (*types.Transaction, error) {
	return _SystemOwner.contract.Transact(opts, "deleteOwner", i)
}

// DeleteOwner is a paid mutator transaction binding the contract method 0x8d257332.
//
// Solidity: function deleteOwner(i uint16) returns()
func (_SystemOwner *SystemOwnerSession) DeleteOwner(i uint16) (*types.Transaction, error) {
	return _SystemOwner.Contract.DeleteOwner(&_SystemOwner.TransactOpts, i)
}

// DeleteOwner is a paid mutator transaction binding the contract method 0x8d257332.
//
// Solidity: function deleteOwner(i uint16) returns()
func (_SystemOwner *SystemOwnerTransactorSession) DeleteOwner(i uint16) (*types.Transaction, error) {
	return _SystemOwner.Contract.DeleteOwner(&_SystemOwner.TransactOpts, i)
}

// IsOwner is a paid mutator transaction binding the contract method 0x2f54bf6e.
//
// Solidity: function isOwner(owner address) returns(bool)
func (_SystemOwner *SystemOwnerTransactor) IsOwner(opts *bind.TransactOpts, owner common.Address) (*types.Transaction, error) {
	return _SystemOwner.contract.Transact(opts, "isOwner", owner)
}

// IsOwner is a paid mutator transaction binding the contract method 0x2f54bf6e.
//
// Solidity: function isOwner(owner address) returns(bool)
func (_SystemOwner *SystemOwnerSession) IsOwner(owner common.Address) (*types.Transaction, error) {
	return _SystemOwner.Contract.IsOwner(&_SystemOwner.TransactOpts, owner)
}

// IsOwner is a paid mutator transaction binding the contract method 0x2f54bf6e.
//
// Solidity: function isOwner(owner address) returns(bool)
func (_SystemOwner *SystemOwnerTransactorSession) IsOwner(owner common.Address) (*types.Transaction, error) {
	return _SystemOwner.Contract.IsOwner(&_SystemOwner.TransactOpts, owner)
}

// SetOwner is a paid mutator transaction binding the contract method 0x95a70863.
//
// Solidity: function setOwner(i uint16, owner address) returns()
func (_SystemOwner *SystemOwnerTransactor) SetOwner(opts *bind.TransactOpts, i uint16, owner common.Address) (*types.Transaction, error) {
	return _SystemOwner.contract.Transact(opts, "setOwner", i, owner)
}

// SetOwner is a paid mutator transaction binding the contract method 0x95a70863.
//
// Solidity: function setOwner(i uint16, owner address) returns()
func (_SystemOwner *SystemOwnerSession) SetOwner(i uint16, owner common.Address) (*types.Transaction, error) {
	return _SystemOwner.Contract.SetOwner(&_SystemOwner.TransactOpts, i, owner)
}

// SetOwner is a paid mutator transaction binding the contract method 0x95a70863.
//
// Solidity: function setOwner(i uint16, owner address) returns()
func (_SystemOwner *SystemOwnerTransactorSession) SetOwner(i uint16, owner common.Address) (*types.Transaction, error) {
	return _SystemOwner.Contract.SetOwner(&_SystemOwner.TransactOpts, i, owner)
}

// TransferOwnership is a paid mutator transaction binding the contract method 0xf2fde38b.
//
// Solidity: function transferOwnership(newOwner address) returns()
func (_SystemOwner *SystemOwnerTransactor) TransferOwnership(opts *bind.TransactOpts, newOwner common.Address) (*types.Transaction, error) {
	return _SystemOwner.contract.Transact(opts, "transferOwnership", newOwner)
}

// TransferOwnership is a paid mutator transaction binding the contract method 0xf2fde38b.
//
// Solidity: function transferOwnership(newOwner address) returns()
func (_SystemOwner *SystemOwnerSession) TransferOwnership(newOwner common.Address) (*types.Transaction, error) {
	return _SystemOwner.Contract.TransferOwnership(&_SystemOwner.TransactOpts, newOwner)
}

// TransferOwnership is a paid mutator transaction binding the contract method 0xf2fde38b.
//
// Solidity: function transferOwnership(newOwner address) returns()
func (_SystemOwner *SystemOwnerTransactorSession) TransferOwnership(newOwner common.Address) (*types.Transaction, error) {
	return _SystemOwner.Contract.TransferOwnership(&_SystemOwner.TransactOpts, newOwner)
}

// SystemOwnerOwnershipTransferredIterator is returned from FilterOwnershipTransferred and is used to iterate over the raw logs and unpacked data for OwnershipTransferred events raised by the SystemOwner contract.
type SystemOwnerOwnershipTransferredIterator struct {
	Event *SystemOwnerOwnershipTransferred // Event containing the contract specifics and raw log

	contract *bind.BoundContract // Generic contract to use for unpacking event data
	event    string              // Event name to use for unpacking event data

	logs chan types.Log        // Log channel receiving the found contract events
	sub  ethereum.Subscription // Subscription for errors, completion and termination
	done bool                  // Whether the subscription completed delivering logs
	fail error                 // Occurred error to stop iteration
}

// Next advances the iterator to the subsequent event, returning whether there
// are any more events found. In case of a retrieval or parsing error, false is
// returned and Error() can be queried for the exact failure.
func (it *SystemOwnerOwnershipTransferredIterator) Next() bool {
	// If the iterator failed, stop iterating
	if it.fail != nil {
		return false
	}
	// If the iterator completed, deliver directly whatever's available
	if it.done {
		select {
		case log := <-it.logs:
			it.Event = new(SystemOwnerOwnershipTransferred)
			if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
				it.fail = err
				return false
			}
			it.Event.Raw = log
			return true

		default:
			return false
		}
	}
	// Iterator still in progress, wait for either a data or an error event
	select {
	case log := <-it.logs:
		it.Event = new(SystemOwnerOwnershipTransferred)
		if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
			it.fail = err
			return false
		}
		it.Event.Raw = log
		return true

	case err := <-it.sub.Err():
		it.done = true
		it.fail = err
		return it.Next()
	}
}

// Error returns any retrieval or parsing error occurred during filtering.
func (it *SystemOwnerOwnershipTransferredIterator) Error() error {
	return it.fail
}

// Close terminates the iteration process, releasing any pending underlying
// resources.
func (it *SystemOwnerOwnershipTransferredIterator) Close() error {
	it.sub.Unsubscribe()
	return nil
}

// SystemOwnerOwnershipTransferred represents a OwnershipTransferred event raised by the SystemOwner contract.
type SystemOwnerOwnershipTransferred struct {
	PreviousOwner common.Address
	NewOwner      common.Address
	Raw           types.Log // Blockchain specific contextual infos
}

// FilterOwnershipTransferred is a free log retrieval operation binding the contract event 0x8be0079c531659141344cd1fd0a4f28419497f9722a3daafe3b4186f6b6457e0.
//
// Solidity: event OwnershipTransferred(previousOwner indexed address, newOwner indexed address)
func (_SystemOwner *SystemOwnerFilterer) FilterOwnershipTransferred(opts *bind.FilterOpts, previousOwner []common.Address, newOwner []common.Address) (*SystemOwnerOwnershipTransferredIterator, error) {

	var previousOwnerRule []interface{}
	for _, previousOwnerItem := range previousOwner {
		previousOwnerRule = append(previousOwnerRule, previousOwnerItem)
	}
	var newOwnerRule []interface{}
	for _, newOwnerItem := range newOwner {
		newOwnerRule = append(newOwnerRule, newOwnerItem)
	}

	logs, sub, err := _SystemOwner.contract.FilterLogs(opts, "OwnershipTransferred", previousOwnerRule, newOwnerRule)
	if err != nil {
		return nil, err
	}
	return &SystemOwnerOwnershipTransferredIterator{contract: _SystemOwner.contract, event: "OwnershipTransferred", logs: logs, sub: sub}, nil
}

// WatchOwnershipTransferred is a free log subscription operation binding the contract event 0x8be0079c531659141344cd1fd0a4f28419497f9722a3daafe3b4186f6b6457e0.
//
// Solidity: event OwnershipTransferred(previousOwner indexed address, newOwner indexed address)
func (_SystemOwner *SystemOwnerFilterer) WatchOwnershipTransferred(opts *bind.WatchOpts, sink chan<- *SystemOwnerOwnershipTransferred, previousOwner []common.Address, newOwner []common.Address) (event.Subscription, error) {

	var previousOwnerRule []interface{}
	for _, previousOwnerItem := range previousOwner {
		previousOwnerRule = append(previousOwnerRule, previousOwnerItem)
	}
	var newOwnerRule []interface{}
	for _, newOwnerItem := range newOwner {
		newOwnerRule = append(newOwnerRule, newOwnerItem)
	}

	logs, sub, err := _SystemOwner.contract.WatchLogs(opts, "OwnershipTransferred", previousOwnerRule, newOwnerRule)
	if err != nil {
		return nil, err
	}
	return event.NewSubscription(func(quit <-chan struct{}) error {
		defer sub.Unsubscribe()
		for {
			select {
			case log := <-logs:
				// New log arrived, parse the event and forward to the user
				event := new(SystemOwnerOwnershipTransferred)
				if err := _SystemOwner.contract.UnpackLog(event, "OwnershipTransferred", log); err != nil {
					return err
				}
				event.Raw = log

				select {
				case sink <- event:
				case err := <-sub.Err():
					return err
				case <-quit:
					return nil
				}
			case err := <-sub.Err():
				return err
			case <-quit:
				return nil
			}
		}
	}), nil
}

// Mit-raExchangeABI is the input ABI used to generate the binding from.
const Mit-raExchangeABI = "[{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"session\",\"type\":\"bytes16\"},{\"name\":\"space\",\"type\":\"bytes16\"},{\"name\":\"offer\",\"type\":\"bytes16\"},{\"name\":\"amount\",\"type\":\"uint256\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"categories\",\"type\":\"uint16[]\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"createActionHit\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"index\",\"type\":\"uint16\"}],\"name\":\"getAdvertiserCoeff\",\"outputs\":[{\"name\":\"\",\"type\":\"int64\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"coeffs\",\"type\":\"int64[]\"}],\"name\":\"setAdvertiserCoeffs\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"index\",\"type\":\"uint16\"}],\"name\":\"getOfferCoeff\",\"outputs\":[{\"name\":\"\",\"type\":\"int64\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"owner\",\"type\":\"bytes16\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"hitPrice\",\"type\":\"uint256\"},{\"name\":\"actionPrice\",\"type\":\"uint256\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"categories\",\"type\":\"uint16[]\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"createOffer\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[],\"name\":\"systemOwner\",\"outputs\":[{\"name\":\"\",\"type\":\"address\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"owner\",\"type\":\"address\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"rank\",\"type\":\"uint8\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"createAdvertiser\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"index\",\"type\":\"uint16\"}],\"name\":\"getAdSpaceCoeff\",\"outputs\":[{\"name\":\"\",\"type\":\"int64\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"owner\",\"type\":\"bytes16\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"url\",\"type\":\"string\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"categories\",\"type\":\"uint16[]\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"updateAdSpace\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"storageAddress\",\"type\":\"address\"}],\"name\":\"setStorageAddress\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"systemOwnerAddress\",\"type\":\"address\"}],\"name\":\"setSystemOwner\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"session\",\"type\":\"bytes16\"},{\"name\":\"space\",\"type\":\"bytes16\"},{\"name\":\"offer\",\"type\":\"bytes16\"},{\"name\":\"amount\",\"type\":\"uint256\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"categories\",\"type\":\"uint16[]\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"updateActionHit\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[],\"name\":\"coeff\",\"outputs\":[{\"name\":\"\",\"type\":\"address\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"coeffs\",\"type\":\"int64[]\"}],\"name\":\"setPublisherCoeffs\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"owner\",\"type\":\"address\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"rank\",\"type\":\"uint8\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"updateAdvertiser\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[],\"name\":\"store\",\"outputs\":[{\"name\":\"\",\"type\":\"address\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"coeffAddress\",\"type\":\"address\"}],\"name\":\"setCoeffAddress\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"owner\",\"type\":\"address\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"rank\",\"type\":\"uint8\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"createPublisher\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"owner\",\"type\":\"address\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"rank\",\"type\":\"uint8\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"updatePublisher\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"session\",\"type\":\"bytes16\"},{\"name\":\"space\",\"type\":\"bytes16\"},{\"name\":\"offer\",\"type\":\"bytes16\"},{\"name\":\"amount\",\"type\":\"uint256\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"categories\",\"type\":\"uint16[]\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"updateDisplayHit\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"owner\",\"type\":\"bytes16\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"hitPrice\",\"type\":\"uint256\"},{\"name\":\"actionPrice\",\"type\":\"uint256\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"categories\",\"type\":\"uint16[]\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"updateOffer\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"amount\",\"type\":\"uint256\"}],\"name\":\"transactHit\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"coeffs\",\"type\":\"int64[]\"}],\"name\":\"setOfferCoeffs\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"index\",\"type\":\"uint16\"}],\"name\":\"getPublisherCoeff\",\"outputs\":[{\"name\":\"\",\"type\":\"int64\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"coeffs\",\"type\":\"int64[]\"}],\"name\":\"setAdSpaceCoeffs\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"owner\",\"type\":\"bytes16\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"url\",\"type\":\"string\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"categories\",\"type\":\"uint16[]\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"createAdSpace\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"session\",\"type\":\"bytes16\"},{\"name\":\"space\",\"type\":\"bytes16\"},{\"name\":\"offer\",\"type\":\"bytes16\"},{\"name\":\"amount\",\"type\":\"uint256\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"categories\",\"type\":\"uint16[]\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"createDisplayHit\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"inputs\":[{\"name\":\"storageAddress\",\"type\":\"address\"},{\"name\":\"coeffAddress\",\"type\":\"address\"},{\"name\":\"systemOwnerAddress\",\"type\":\"address\"}],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"constructor\"},{\"anonymous\":false,\"inputs\":[{\"indexed\":true,\"name\":\"id\",\"type\":\"bytes16\"},{\"indexed\":true,\"name\":\"owner\",\"type\":\"address\"}],\"name\":\"PublisherCreated\",\"type\":\"event\"},{\"anonymous\":false,\"inputs\":[{\"indexed\":true,\"name\":\"id\",\"type\":\"bytes16\"},{\"indexed\":true,\"name\":\"owner\",\"type\":\"address\"}],\"name\":\"AdvertiserCreated\",\"type\":\"event\"},{\"anonymous\":false,\"inputs\":[{\"indexed\":true,\"name\":\"id\",\"type\":\"bytes16\"},{\"indexed\":true,\"name\":\"owner\",\"type\":\"bytes16\"}],\"name\":\"AdSpaceCreated\",\"type\":\"event\"},{\"anonymous\":false,\"inputs\":[{\"indexed\":true,\"name\":\"id\",\"type\":\"bytes16\"},{\"indexed\":true,\"name\":\"owner\",\"type\":\"bytes16\"}],\"name\":\"OfferCreated\",\"type\":\"event\"},{\"anonymous\":false,\"inputs\":[{\"indexed\":true,\"name\":\"id\",\"type\":\"bytes16\"},{\"indexed\":true,\"name\":\"offer\",\"type\":\"bytes16\"},{\"indexed\":false,\"name\":\"amount\",\"type\":\"uint256\"}],\"name\":\"HitCreated\",\"type\":\"event\"},{\"anonymous\":false,\"inputs\":[{\"indexed\":true,\"name\":\"id\",\"type\":\"bytes16\"},{\"indexed\":false,\"name\":\"amount\",\"type\":\"uint256\"}],\"name\":\"HitTransacted\",\"type\":\"event\"}]"

// Mit-raExchangeBin is the compiled bytecode used for deploying new contracts.
const Mit-raExchangeBin = `0x608060405234801561001057600080fd5b5060405160608061495f83398101604090815281516020830151919092015160018054600160a060020a0319908116600160a060020a0395861617909155600280548216938516939093179092556000805490921692169190911781556148e290819061007d90396000f30060806040526004361061015e5763ffffffff7c010000000000000000000000000000000000000000000000000000000060003504166301c1ba8d811461016357806306e7bdb1146102235780630c2bf561146102655780631c44f0a4146102c95780632f8ef80f146102f257806333779254146103eb57806341837e171461041c57806345e09d88146104dd57806348047f001461050657806359b910d614610630578063621eb9a2146106515780638363d03d1461067257806387b261ad14610730578063895b5111146102655780638ed752df14610745578063975057e7146108065780639dd8a1061461081b578063a33924171461083c578063aa569e50146108fd578063bde170d4146109be578063c50c53f414610a7c578063dfc3cfca14610b75578063e1df603514610b9a578063eaa9a80014610223578063fa362e7914610bfe578063faa1cd3614610c62578063fd0dec4814610d8c575b600080fd5b34801561016f57600080fd5b50604080516020600460a43581810135601f81018490048402850184019095528484526102219482356001608060020a03199081169560248035831696604435841696606435909416956084359536959460c49490939201918190840183828082843750506040805187358901803560208181028481018201909552818452989b9a9989019892975090820195509350839250850190849080828437509497505050923560ff169350610e4a92505050565b005b34801561022f57600080fd5b5061024c6001608060020a03196004351661ffff602435166111d5565b60408051600792830b90920b8252519081900360200190f35b34801561027157600080fd5b506040805160206004602480358281013584810280870186019097528086526102219684356001608060020a031916963696604495919490910192918291850190849080828437509497506113ed9650505050505050565b3480156102d557600080fd5b5061024c6001608060020a03196004351661ffff602435166116ad565b3480156102fe57600080fd5b50604080516020600460443581810135601f81018490048402850184019095528484526102219482356001608060020a03199081169560248035909216953695946064949293019190819084018382808284375050604080516020888301358a018035601f8101839004830284018301909452838352979a89359a8a8301359a91999098506060909101965091945090810192508190840183828082843750506040805187358901803560208181028481018201909552818452989b9a9989019892975090820195509350839250850190849080828437509497505050923560ff16935061180792505050565b3480156103f757600080fd5b50610400611c17565b60408051600160a060020a039092168252519081900360200190f35b34801561042857600080fd5b50604080516020600460443581810135601f81018490048402850184019095528484526102219482356001608060020a0319169460248035600160a060020a03169536959460649492019190819084018382808284375050604080516020601f89358b018035918201839004830284018301909452808352979a9998810197919650918201945092508291508401838280828437509497505060ff8535811696506020909501359094169350611c2692505050565b3480156104e957600080fd5b5061024c6001608060020a03196004351661ffff60243516611fe6565b34801561051257600080fd5b50604080516020600460443581810135601f81018490048402850184019095528484526102219482356001608060020a03199081169560248035909216953695946064949293019190819084018382808284375050604080516020601f89358b018035918201839004830284018301909452808352979a99988101979196509182019450925082915084018382808284375050604080516020601f89358b018035918201839004830284018301909452808352979a999881019791965091820194509250829150840183828082843750506040805187358901803560208181028481018201909552818452989b9a9989019892975090820195509350839250850190849080828437509497505050923560ff16935061217792505050565b34801561063c57600080fd5b50610221600160a060020a03600435166125db565b34801561065d57600080fd5b50610221600160a060020a0360043516612696565b34801561067e57600080fd5b50604080516020600460a43581810135601f81018490048402850184019095528484526102219482356001608060020a03199081169560248035831696604435841696606435909416956084359536959460c49490939201918190840183828082843750506040805187358901803560208181028481018201909552818452989b9a9989019892975090820195509350839250850190849080828437509497505050923560ff16935061275192505050565b34801561073c57600080fd5b50610400612a9a565b34801561075157600080fd5b50604080516020600460443581810135601f81018490048402850184019095528484526102219482356001608060020a0319169460248035600160a060020a03169536959460649492019190819084018382808284375050604080516020601f89358b018035918201839004830284018301909452808352979a9998810197919650918201945092508291508401838280828437509497505060ff8535811696506020909501359094169350612aa992505050565b34801561081257600080fd5b50610400612e2d565b34801561082757600080fd5b50610221600160a060020a0360043516612e3c565b34801561084857600080fd5b50604080516020600460443581810135601f81018490048402850184019095528484526102219482356001608060020a0319169460248035600160a060020a03169536959460649492019190819084018382808284375050604080516020601f89358b018035918201839004830284018301909452808352979a9998810197919650918201945092508291508401838280828437509497505060ff8535811696506020909501359094169350612ef792505050565b34801561090957600080fd5b50604080516020600460443581810135601f81018490048402850184019095528484526102219482356001608060020a0319169460248035600160a060020a03169536959460649492019190819084018382808284375050604080516020601f89358b018035918201839004830284018301909452808352979a9998810197919650918201945092508291508401838280828437509497505060ff85358116965060209095013590941693506132b892505050565b3480156109ca57600080fd5b50604080516020600460a43581810135601f81018490048402850184019095528484526102219482356001608060020a03199081169560248035831696604435841696606435909416956084359536959460c49490939201918190840183828082843750506040805187358901803560208181028481018201909552818452989b9a9989019892975090820195509350839250850190849080828437509497505050923560ff1693506134fe92505050565b348015610a8857600080fd5b50604080516020600460443581810135601f81018490048402850184019095528484526102219482356001608060020a03199081169560248035909216953695946064949293019190819084018382808284375050604080516020888301358a018035601f8101839004830284018301909452838352979a89359a8a8301359a91999098506060909101965091945090810192508190840183828082843750506040805187358901803560208181028481018201909552818452989b9a9989019892975090820195509350839250850190849080828437509497505050923560ff16935061371492505050565b348015610b8157600080fd5b506102216001608060020a031960043516602435613a9a565b348015610ba657600080fd5b506040805160206004602480358281013584810280870186019097528086526102219684356001608060020a03191696369660449591949091019291829185019084908082843750949750613df09650505050505050565b348015610c0a57600080fd5b506040805160206004602480358281013584810280870186019097528086526102219684356001608060020a03191696369660449591949091019291829185019084908082843750949750613fcf9650505050505050565b348015610c6e57600080fd5b50604080516020600460443581810135601f81018490048402850184019095528484526102219482356001608060020a03199081169560248035909216953695946064949293019190819084018382808284375050604080516020601f89358b018035918201839004830284018301909452808352979a99988101979196509182019450925082915084018382808284375050604080516020601f89358b018035918201839004830284018301909452808352979a999881019791965091820194509250829150840183828082843750506040805187358901803560208181028481018201909552818452989b9a9989019892975090820195509350839250850190849080828437509497505050923560ff1693506141e592505050565b348015610d9857600080fd5b50604080516020600460a43581810135601f81018490048402850184019095528484526102219482356001608060020a03199081169560248035831696604435841696606435909416956084359536959460c49490939201918190840183828082843750506040805187358901803560208181028481018201909552818452989b9a9989019892975090820195509350839250850190849080828437509497505050923560ff16935061468192505050565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b158015610e9c57600080fd5b505af1158015610eb0573d6000803e3d6000fd5b505050506040513d6020811015610ec657600080fd5b50511515610ed357600080fd5b6001546040805160e260020a6327b8eb510281526001608060020a03198c1660048201529051600160a060020a0390921691639ee3ad449160248082019260009290919082900301818387803b158015610f2c57600080fd5b505af1158015610f40573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f19168201604052610100811015610f6a57600080fd5b8151602083015160408401516060850151608086015160a087015160c0880180519698959794969395929491939183019291602060020a811115610fad57600080fd5b82016020810184811115610fc057600080fd5b8151602060020a811182820187101715610fd957600080fd5b50505060200151985060009750610ff39650505050505050565b816005811115610fff57fe5b1461100957600080fd5b60015460405160008051602061489783398151915281526001608060020a03198b1660048201908152600160a060020a039092169163ff2e6ec4918c916002918d918d918d918d918d918d918d9190602401895b60ff1681526001608060020a0319808a1660208301528881166040830152871660608201526080810186905260a081019060c081019060e0018460058111156110a257fe5b60ff168152602001838103835286818151815260200191508051906020019080838360005b838110156110df5781810151838201526020016110c7565b50505050905090810190601f16801561110c5780820380516001836020036101000a031916815260200191505b508381038252855181528551602091820191808801910280838360005b83811015611141578181015183820152602001611129565b505050509050019b505050505050505050505050600060405180830381600087803b15801561116f57600080fd5b505af1158015611183573d6000803e3d6000fd5b50506040805188815290516001608060020a0319808b1694508d1692507fb1ed61a63a8c9a4a24619a622cfb89000d005cbdd391a707fcc292ba57c1fb639181900360200190a3505050505050505050565b6001546040805160e260020a631d4837450281526001608060020a03198516600482015290516000928392600160a060020a0390911691637520dd1491602480820192869290919082900301818387803b15801561123257600080fd5b505af1158015611246573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260e081101561126f57600080fd5b8151602083015160408401516060850180519395929491939183019291602060020a81111561129d57600080fd5b820160208101848111156112b057600080fd5b8151602060020a8111828201871017156112c957600080fd5b50509291906020018051602060020a8111156112e457600080fd5b820160208101848111156112f757600080fd5b8151602060020a81118282018710171561131057600080fd5b50505060400151965060009550611328945050505050565b81600581111561133457fe5b141561133f57600080fd5b600254604080517fbd40db2d0000000000000000000000000000000000000000000000000000000081526001608060020a03198716600482015261ffff861660248201529051600160a060020a039092169163bd40db2d916044808201926020929091908290030181600087803b1580156113b957600080fd5b505af11580156113cd573d6000803e3d6000fd5b505050506040513d60208110156113e357600080fd5b5051949350505050565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b15801561143f57600080fd5b505af1158015611453573d6000803e3d6000fd5b505050506040513d602081101561146957600080fd5b5051151561147657600080fd5b6001546040805160e260020a631d4837450281526001608060020a0319861660048201529051600160a060020a0390921691637520dd149160248082019260009290919082900301818387803b1580156114cf57600080fd5b505af11580156114e3573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260e081101561150c57600080fd5b8151602083015160408401516060850180519395929491939183019291602060020a81111561153a57600080fd5b8201602081018481111561154d57600080fd5b8151602060020a81118282018710171561156657600080fd5b50509291906020018051602060020a81111561158157600080fd5b8201602081018481111561159457600080fd5b8151602060020a8111828201871017156115ad57600080fd5b505050604001519650600095506115c5945050505050565b8160058111156115d157fe5b14156115dc57600080fd5b600254604080517f83a4c9c30000000000000000000000000000000000000000000000000000000081526001608060020a031986166004820190815260248201928352855160448301528551600160a060020a03909416936383a4c9c39388938893926064909101906020808601910280838360005b8381101561166a578181015183820152602001611652565b505050509050019350505050600060405180830381600087803b15801561169057600080fd5b505af11580156116a4573d6000803e3d6000fd5b50505050505050565b6001546040805160e060020a63c32d869b0281526001608060020a03198516600482015290516000928392600160a060020a039091169163c32d869b91602480820192869290919082900301818387803b15801561170a57600080fd5b505af115801561171e573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260e081101561174757600080fd5b8151602083015160408401805192949193820192602060020a81111561176c57600080fd5b8201602081018481111561177f57600080fd5b8151602060020a81118282018710171561179857600080fd5b50506020820151604083015160609093018051929591949192602060020a8111156117c257600080fd5b820160208101848111156117d557600080fd5b8151602060020a8111828201871017156117ee57600080fd5b5050506020015197506000965061132895505050505050565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b15801561185957600080fd5b505af115801561186d573d6000803e3d6000fd5b505050506040513d602081101561188357600080fd5b5051151561189057600080fd5b6001546040805160e060020a63c32d869b0281526001608060020a03198c1660048201529051600160a060020a039092169163c32d869b9160248082019260009290919082900301818387803b1580156118e957600080fd5b505af11580156118fd573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260e081101561192657600080fd5b8151602083015160408401805192949193820192602060020a81111561194b57600080fd5b8201602081018481111561195e57600080fd5b8151602060020a81118282018710171561197757600080fd5b50506020820151604083015160609093018051929591949192602060020a8111156119a157600080fd5b820160208101848111156119b457600080fd5b8151602060020a8111828201871017156119cd57600080fd5b505050602001519750600096506119e695505050505050565b8160058111156119f257fe5b146119fc57600080fd5b6001546040517ff26b7f9b0000000000000000000000000000000000000000000000000000000081526001608060020a0319808c1660048301908152908b1660248301526064820189905260848201889052600160a060020a039092169163f26b7f9b918c918c918c918c918c918c918c918c91604481019060a481019060c481019060e401856005811115611a8e57fe5b60ff16815260200184810384528a818151815260200191508051906020019080838360005b83811015611acb578181015183820152602001611ab3565b50505050905090810190601f168015611af85780820380516001836020036101000a031916815260200191505b50848103835287518152875160209182019189019080838360005b83811015611b2b578181015183820152602001611b13565b50505050905090810190601f168015611b585780820380516001836020036101000a031916815260200191505b508481038252865181528651602091820191808901910280838360005b83811015611b8d578181015183820152602001611b75565b505050509050019b505050505050505050505050600060405180830381600087803b158015611bbb57600080fd5b505af1158015611bcf573d6000803e3d6000fd5b50506040516001608060020a0319808c1693508c1691507f3452c2f4f5fd20f28b87971b0ef62e650904e6706f96823bd746ec1050abd67990600090a3505050505050505050565b600054600160a060020a031681565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b158015611c7857600080fd5b505af1158015611c8c573d6000803e3d6000fd5b505050506040513d6020811015611ca257600080fd5b50511515611caf57600080fd5b6001546040805160e260020a631d4837450281526001608060020a03198a1660048201529051600160a060020a0390921691637520dd149160248082019260009290919082900301818387803b158015611d0857600080fd5b505af1158015611d1c573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260e0811015611d4557600080fd5b8151602083015160408401516060850180519395929491939183019291602060020a811115611d7357600080fd5b82016020810184811115611d8657600080fd5b8151602060020a811182820187101715611d9f57600080fd5b50509291906020018051602060020a811115611dba57600080fd5b82016020810184811115611dcd57600080fd5b8151602060020a811182820187101715611de657600080fd5b50505060400151965060009550611dfe945050505050565b816005811115611e0a57fe5b14611e1457600080fd5b60015460405160e060020a634034aad90281526001608060020a0319891660048201908152600160a060020a038981166024840152600260448401819052931692634034aad9928b928b92918b918b918b918b916064810190608481019060a401856006811115611e8157fe5b60ff168152602001846005811115611e9557fe5b60ff168152602001838103835287818151815260200191508051906020019080838360005b83811015611ed2578181015183820152602001611eba565b50505050905090810190601f168015611eff5780820380516001836020036101000a031916815260200191505b50838103825286518152865160209182019188019080838360005b83811015611f32578181015183820152602001611f1a565b50505050905090810190601f168015611f5f5780820380516001836020036101000a031916815260200191505b509950505050505050505050600060405180830381600087803b158015611f8557600080fd5b505af1158015611f99573d6000803e3d6000fd5b5050604051600160a060020a03891692506001608060020a03198a1691507fc1d8ed79dee2680263f53981ac2d751cebe1536ff6933bb06f28769e54b6c49a90600090a350505050505050565b6001546040805160e160020a634278fcb30281526001608060020a03198516600482015290516000928392600160a060020a03909116916384f1f96691602480820192869290919082900301818387803b15801561204357600080fd5b505af1158015612057573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260c081101561208057600080fd5b8151602083015160408401805192949193820192602060020a8111156120a557600080fd5b820160208101848111156120b857600080fd5b8151602060020a8111828201871017156120d157600080fd5b50509291906020018051602060020a8111156120ec57600080fd5b820160208101848111156120ff57600080fd5b8151602060020a81118282018710171561211857600080fd5b50509291906020018051602060020a81111561213357600080fd5b8201602081018481111561214657600080fd5b8151602060020a81118282018710171561215f57600080fd5b50505060200151965060009550611328945050505050565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b1580156121c957600080fd5b505af11580156121dd573d6000803e3d6000fd5b505050506040513d60208110156121f357600080fd5b5051151561220057600080fd5b6001546040805160e160020a634278fcb30281526001608060020a03198b1660048201529051600160a060020a03909216916384f1f9669160248082019260009290919082900301818387803b15801561225957600080fd5b505af115801561226d573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260c081101561229657600080fd5b8151602083015160408401805192949193820192602060020a8111156122bb57600080fd5b820160208101848111156122ce57600080fd5b8151602060020a8111828201871017156122e757600080fd5b50509291906020018051602060020a81111561230257600080fd5b8201602081018481111561231557600080fd5b8151602060020a81118282018710171561232e57600080fd5b50509291906020018051602060020a81111561234957600080fd5b8201602081018481111561235c57600080fd5b8151602060020a81118282018710171561237557600080fd5b5050506020015196506000955061238d945050505050565b81600581111561239957fe5b14156123a457600080fd5b6001546040517f7e4a3d4f0000000000000000000000000000000000000000000000000000000081526001608060020a0319808b1660048301908152908a166024830152600160a060020a0390921691637e4a3d4f918b918b918b918b918b918b918b919060448101906064810190608481019060a481019060c40186600581111561242c57fe5b60ff16815260200185810385528a818151815260200191508051906020019080838360005b83811015612469578181015183820152602001612451565b50505050905090810190601f1680156124965780820380516001836020036101000a031916815260200191505b5085810384528951815289516020918201918b019080838360005b838110156124c95781810151838201526020016124b1565b50505050905090810190601f1680156124f65780820380516001836020036101000a031916815260200191505b5085810383528851815288516020918201918a019080838360005b83811015612529578181015183820152602001612511565b50505050905090810190601f1680156125565780820380516001836020036101000a031916815260200191505b508581038252875181528751602091820191808a01910280838360005b8381101561258b578181015183820152602001612573565b505050509050019b505050505050505050505050600060405180830381600087803b1580156125b957600080fd5b505af11580156125cd573d6000803e3d6000fd5b505050505050505050505050565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921692632f54bf6e92602480820193602093909283900390910190829087803b15801561263057600080fd5b505af1158015612644573d6000803e3d6000fd5b505050506040513d602081101561265a57600080fd5b5051151561266757600080fd5b6001805473ffffffffffffffffffffffffffffffffffffffff1916600160a060020a0392909216919091179055565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921692632f54bf6e92602480820193602093909283900390910190829087803b1580156126eb57600080fd5b505af11580156126ff573d6000803e3d6000fd5b505050506040513d602081101561271557600080fd5b5051151561272257600080fd5b6000805473ffffffffffffffffffffffffffffffffffffffff1916600160a060020a0392909216919091179055565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b1580156127a357600080fd5b505af11580156127b7573d6000803e3d6000fd5b505050506040513d60208110156127cd57600080fd5b505115156127da57600080fd5b6001546040805160e260020a6327b8eb510281526001608060020a03198c1660048201529051600160a060020a0390921691639ee3ad449160248082019260009290919082900301818387803b15801561283357600080fd5b505af1158015612847573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405261010081101561287157600080fd5b8151602083015160408401516060850151608086015160a087015160c0880180519698959794969395929491939183019291602060020a8111156128b457600080fd5b820160208101848111156128c757600080fd5b8151602060020a8111828201871017156128e057600080fd5b505050602001519850600097506128fa9650505050505050565b81600581111561290657fe5b141561291157600080fd5b60015460405160008051602061489783398151915281526001608060020a03198b1660048201908152600160a060020a039092169163ff2e6ec4918c916002918d918d918d918d918d918d918d9190602401895b60ff1681526001608060020a0319808a1660208301528881166040830152871660608201526080810186905260a081019060c081019060e0018460058111156129aa57fe5b60ff168152602001838103835286818151815260200191508051906020019080838360005b838110156129e75781810151838201526020016129cf565b50505050905090810190601f168015612a145780820380516001836020036101000a031916815260200191505b508381038252855181528551602091820191808801910280838360005b83811015612a49578181015183820152602001612a31565b505050509050019b505050505050505050505050600060405180830381600087803b158015612a7757600080fd5b505af1158015612a8b573d6000803e3d6000fd5b50505050505050505050505050565b600254600160a060020a031681565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b158015612afb57600080fd5b505af1158015612b0f573d6000803e3d6000fd5b505050506040513d6020811015612b2557600080fd5b50511515612b3257600080fd5b6001546040805160e260020a631d4837450281526001608060020a03198a1660048201529051600160a060020a0390921691637520dd149160248082019260009290919082900301818387803b158015612b8b57600080fd5b505af1158015612b9f573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260e0811015612bc857600080fd5b8151602083015160408401516060850180519395929491939183019291602060020a811115612bf657600080fd5b82016020810184811115612c0957600080fd5b8151602060020a811182820187101715612c2257600080fd5b50509291906020018051602060020a811115612c3d57600080fd5b82016020810184811115612c5057600080fd5b8151602060020a811182820187101715612c6957600080fd5b50505060400151965060009550612c81945050505050565b816005811115612c8d57fe5b1415612c9857600080fd5b60015460405160e060020a634034aad90281526001608060020a0319891660048201908152600160a060020a03898116602484015290921691634034aad9918a918a916002918b918b918b918b9190604401865b60ff1681526020018060200180602001856006811115612d0857fe5b60ff168152602001846005811115612d1c57fe5b60ff168152602001838103835287818151815260200191508051906020019080838360005b83811015612d59578181015183820152602001612d41565b50505050905090810190601f168015612d865780820380516001836020036101000a031916815260200191505b50838103825286518152865160209182019188019080838360005b83811015612db9578181015183820152602001612da1565b50505050905090810190601f168015612de65780820380516001836020036101000a031916815260200191505b509950505050505050505050600060405180830381600087803b158015612e0c57600080fd5b505af1158015612e20573d6000803e3d6000fd5b5050505050505050505050565b600154600160a060020a031681565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921692632f54bf6e92602480820193602093909283900390910190829087803b158015612e9157600080fd5b505af1158015612ea5573d6000803e3d6000fd5b505050506040513d6020811015612ebb57600080fd5b50511515612ec857600080fd5b6002805473ffffffffffffffffffffffffffffffffffffffff1916600160a060020a0392909216919091179055565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b158015612f4957600080fd5b505af1158015612f5d573d6000803e3d6000fd5b505050506040513d6020811015612f7357600080fd5b50511515612f8057600080fd5b6001546040805160e260020a631d4837450281526001608060020a03198a1660048201529051600160a060020a0390921691637520dd149160248082019260009290919082900301818387803b158015612fd957600080fd5b505af1158015612fed573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260e081101561301657600080fd5b8151602083015160408401516060850180519395929491939183019291602060020a81111561304457600080fd5b8201602081018481111561305757600080fd5b8151602060020a81118282018710171561307057600080fd5b50509291906020018051602060020a81111561308b57600080fd5b8201602081018481111561309e57600080fd5b8151602060020a8111828201871017156130b757600080fd5b505050604001519650600095506130cf945050505050565b8160058111156130db57fe5b146130e557600080fd5b6001805460405160e060020a634034aad90281526001608060020a03198a1660048201908152600160a060020a038a8116602484015290921692634034aad9928b928b92918b918b918b918b91906044018660ff168152602001806020018060200185600681111561315357fe5b60ff16815260200184600581111561316757fe5b60ff168152602001838103835287818151815260200191508051906020019080838360005b838110156131a457818101518382015260200161318c565b50505050905090810190601f1680156131d15780820380516001836020036101000a031916815260200191505b50838103825286518152865160209182019188019080838360005b838110156132045781810151838201526020016131ec565b50505050905090810190601f1680156132315780820380516001836020036101000a031916815260200191505b509950505050505050505050600060405180830381600087803b15801561325757600080fd5b505af115801561326b573d6000803e3d6000fd5b5050604051600160a060020a03891692506001608060020a03198a1691507f64f6c400b090ba2031d25a03826d652b5d62a7c18b5f523b38852a9c30b6910390600090a350505050505050565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b15801561330a57600080fd5b505af115801561331e573d6000803e3d6000fd5b505050506040513d602081101561333457600080fd5b5051151561334157600080fd5b6001546040805160e260020a631d4837450281526001608060020a03198a1660048201529051600160a060020a0390921691637520dd149160248082019260009290919082900301818387803b15801561339a57600080fd5b505af11580156133ae573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260e08110156133d757600080fd5b8151602083015160408401516060850180519395929491939183019291602060020a81111561340557600080fd5b8201602081018481111561341857600080fd5b8151602060020a81118282018710171561343157600080fd5b50509291906020018051602060020a81111561344c57600080fd5b8201602081018481111561345f57600080fd5b8151602060020a81118282018710171561347857600080fd5b50505060400151965060009550613490945050505050565b81600581111561349c57fe5b14156134a757600080fd5b6001805460405160e060020a634034aad90281526001608060020a03198a1660048201908152600160a060020a038a8116602484015290921692634034aad9928b928b92918b918b918b918b919060440186612cec565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b15801561355057600080fd5b505af1158015613564573d6000803e3d6000fd5b505050506040513d602081101561357a57600080fd5b5051151561358757600080fd5b6001546040805160e260020a6327b8eb510281526001608060020a03198c1660048201529051600160a060020a0390921691639ee3ad449160248082019260009290919082900301818387803b1580156135e057600080fd5b505af11580156135f4573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405261010081101561361e57600080fd5b8151602083015160408401516060850151608086015160a087015160c0880180519698959794969395929491939183019291602060020a81111561366157600080fd5b8201602081018481111561367457600080fd5b8151602060020a81118282018710171561368d57600080fd5b505050602001519850600097506136a79650505050505050565b8160058111156136b357fe5b14156136be57600080fd5b6001805460405160008051602061489783398151915281526001608060020a03198c1660048201908152600160a060020a039092169263ff2e6ec4928d928d918d918d918d918d918d918d919060240189612965565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b15801561376657600080fd5b505af115801561377a573d6000803e3d6000fd5b505050506040513d602081101561379057600080fd5b5051151561379d57600080fd5b6001546040805160e060020a63c32d869b0281526001608060020a03198c1660048201529051600160a060020a039092169163c32d869b9160248082019260009290919082900301818387803b1580156137f657600080fd5b505af115801561380a573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260e081101561383357600080fd5b8151602083015160408401805192949193820192602060020a81111561385857600080fd5b8201602081018481111561386b57600080fd5b8151602060020a81118282018710171561388457600080fd5b50506020820151604083015160609093018051929591949192602060020a8111156138ae57600080fd5b820160208101848111156138c157600080fd5b8151602060020a8111828201871017156138da57600080fd5b505050602001519750600096506138f395505050505050565b8160058111156138ff57fe5b141561390a57600080fd5b6001546040517ff26b7f9b0000000000000000000000000000000000000000000000000000000081526001608060020a0319808c1660048301908152908b1660248301526064820189905260848201889052600160a060020a039092169163f26b7f9b918c918c918c918c918c918c918c918c91604481019060a481019060c481019060e40185600581111561399c57fe5b60ff16815260200184810384528a818151815260200191508051906020019080838360005b838110156139d95781810151838201526020016139c1565b50505050905090810190601f168015613a065780820380516001836020036101000a031916815260200191505b50848103835287518152875160209182019189019080838360005b83811015613a39578181015183820152602001613a21565b50505050905090810190601f168015613a665780820380516001836020036101000a031916815260200191505b5084810382528651815286516020918201918089019102808383600083811015612a49578181015183820152602001612a31565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b158015613aec57600080fd5b505af1158015613b00573d6000803e3d6000fd5b505050506040513d6020811015613b1657600080fd5b50511515613b2357600080fd5b6001546040805160e260020a6327b8eb510281526001608060020a0319861660048201529051600160a060020a0390921691639ee3ad449160248082019260009290919082900301818387803b158015613b7c57600080fd5b505af1158015613b90573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f19168201604052610100811015613bba57600080fd5b8151602083015160408401516060850151608086015160a087015160c0880180519698959794969395929491939183019291602060020a811115613bfd57600080fd5b82016020810184811115613c1057600080fd5b8151602060020a811182820187101715613c2957600080fd5b50505060200151985060009750613c439650505050505050565b816005811115613c4f57fe5b14158015613c6957506005816005811115613c6657fe5b14155b8015613c8157506004816005811115613c7e57fe5b14155b1515613c8c57600080fd5b60015460408051600080825260208201928390526000805160206148978339815191529092526001608060020a031986166024820190815260448201839052606482018390526084820183905260a4820183905260c48201869052600160a060020a039093169263ff2e6ec492879290918291829182918a9160049060e48301610104840161012485018460ff168152602001838103835260008152602001602001838103825285818151815260200191508051906020019060200280838360005b83811015613d66578181015183820152602001613d4e565b505050509050019a5050505050505050505050600060405180830381600087803b158015613d9357600080fd5b505af1158015613da7573d6000803e3d6000fd5b50506040805185815290516001608060020a0319871693507f0beb153826af0cb18373da3640116642aefbb4b6fcf160cba453086102ccea1b92509081900360200190a2505050565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b158015613e4257600080fd5b505af1158015613e56573d6000803e3d6000fd5b505050506040513d6020811015613e6c57600080fd5b50511515613e7957600080fd5b6001546040805160e060020a63c32d869b0281526001608060020a0319861660048201529051600160a060020a039092169163c32d869b9160248082019260009290919082900301818387803b158015613ed257600080fd5b505af1158015613ee6573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260e0811015613f0f57600080fd5b8151602083015160408401805192949193820192602060020a811115613f3457600080fd5b82016020810184811115613f4757600080fd5b8151602060020a811182820187101715613f6057600080fd5b50506020820151604083015160609093018051929591949192602060020a811115613f8a57600080fd5b82016020810184811115613f9d57600080fd5b8151602060020a811182820187101715613fb657600080fd5b505050602001519750600096506115c595505050505050565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b15801561402157600080fd5b505af1158015614035573d6000803e3d6000fd5b505050506040513d602081101561404b57600080fd5b5051151561405857600080fd5b6001546040805160e160020a634278fcb30281526001608060020a0319861660048201529051600160a060020a03909216916384f1f9669160248082019260009290919082900301818387803b1580156140b157600080fd5b505af11580156140c5573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260c08110156140ee57600080fd5b8151602083015160408401805192949193820192602060020a81111561411357600080fd5b8201602081018481111561412657600080fd5b8151602060020a81118282018710171561413f57600080fd5b50509291906020018051602060020a81111561415a57600080fd5b8201602081018481111561416d57600080fd5b8151602060020a81118282018710171561418657600080fd5b50509291906020018051602060020a8111156141a157600080fd5b820160208101848111156141b457600080fd5b8151602060020a8111828201871017156141cd57600080fd5b505050602001519650600095506115c5945050505050565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b15801561423757600080fd5b505af115801561424b573d6000803e3d6000fd5b505050506040513d602081101561426157600080fd5b5051151561426e57600080fd5b6001546040805160e160020a634278fcb30281526001608060020a03198b1660048201529051600160a060020a03909216916384f1f9669160248082019260009290919082900301818387803b1580156142c757600080fd5b505af11580156142db573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f1916820160405260c081101561430457600080fd5b8151602083015160408401805192949193820192602060020a81111561432957600080fd5b8201602081018481111561433c57600080fd5b8151602060020a81118282018710171561435557600080fd5b50509291906020018051602060020a81111561437057600080fd5b8201602081018481111561438357600080fd5b8151602060020a81118282018710171561439c57600080fd5b50509291906020018051602060020a8111156143b757600080fd5b820160208101848111156143ca57600080fd5b8151602060020a8111828201871017156143e357600080fd5b505050602001519650600095506143fb945050505050565b81600581111561440757fe5b1461441157600080fd5b6001546040517f7e4a3d4f0000000000000000000000000000000000000000000000000000000081526001608060020a0319808b1660048301908152908a166024830152600160a060020a0390921691637e4a3d4f918b918b918b918b918b918b918b919060448101906064810190608481019060a481019060c40186600581111561449957fe5b60ff16815260200185810385528a818151815260200191508051906020019080838360005b838110156144d65781810151838201526020016144be565b50505050905090810190601f1680156145035780820380516001836020036101000a031916815260200191505b5085810384528951815289516020918201918b019080838360005b8381101561453657818101518382015260200161451e565b50505050905090810190601f1680156145635780820380516001836020036101000a031916815260200191505b5085810383528851815288516020918201918a019080838360005b8381101561459657818101518382015260200161457e565b50505050905090810190601f1680156145c35780820380516001836020036101000a031916815260200191505b508581038252875181528751602091820191808a01910280838360005b838110156145f85781810151838201526020016145e0565b505050509050019b505050505050505050505050600060405180830381600087803b15801561462657600080fd5b505af115801561463a573d6000803e3d6000fd5b50506040516001608060020a0319808b1693508b1691507f49356dee5ff51d2c6badbfa96d72bbe12dd742c52ea5b1f9a8a52afb92c54d1890600090a35050505050505050565b600080546040805160e160020a6317aa5fb7028152600160a060020a03338116600483015291519190921691632f54bf6e91602480830192602092919082900301818787803b1580156146d357600080fd5b505af11580156146e7573d6000803e3d6000fd5b505050506040513d60208110156146fd57600080fd5b5051151561470a57600080fd5b6001546040805160e260020a6327b8eb510281526001608060020a03198c1660048201529051600160a060020a0390921691639ee3ad449160248082019260009290919082900301818387803b15801561476357600080fd5b505af1158015614777573d6000803e3d6000fd5b505050506040513d6000823e601f3d908101601f191682016040526101008110156147a157600080fd5b8151602083015160408401516060850151608086015160a087015160c0880180519698959794969395929491939183019291602060020a8111156147e457600080fd5b820160208101848111156147f757600080fd5b8151602060020a81118282018710171561481057600080fd5b5050506020015198506000975061482a9650505050505050565b81600581111561483657fe5b1461484057600080fd5b6001805460405160008051602061489783398151915281526001608060020a03198c1660048201908152600160a060020a039092169263ff2e6ec4928d928d918d918d918d918d918d918d91906024018961105d5600ff2e6ec400000000000000000000000000000000000000000000000000000000a165627a7a72305820bd01fe14aa4d14b41c70b4b94ae6af74a73dcae6ac7a597bc5496d82957292980029`

// DeployMit-raExchange deploys a new Ethereum contract, binding an instance of Mit-raExchange to it.
func DeployMit-raExchange(auth *bind.TransactOpts, backend bind.ContractBackend, storageAddress common.Address, coeffAddress common.Address, systemOwnerAddress common.Address) (common.Address, *types.Transaction, *Mit-raExchange, error) {
	parsed, err := abi.JSON(strings.NewReader(Mit-raExchangeABI))
	if err != nil {
		return common.Address{}, nil, nil, err
	}
	address, tx, contract, err := bind.DeployContract(auth, parsed, common.FromHex(Mit-raExchangeBin), backend, storageAddress, coeffAddress, systemOwnerAddress)
	if err != nil {
		return common.Address{}, nil, nil, err
	}
	return address, tx, &Mit-raExchange{Mit-raExchangeCaller: Mit-raExchangeCaller{contract: contract}, Mit-raExchangeTransactor: Mit-raExchangeTransactor{contract: contract}, Mit-raExchangeFilterer: Mit-raExchangeFilterer{contract: contract}}, nil
}

// Mit-raExchange is an auto generated Go binding around an Ethereum contract.
type Mit-raExchange struct {
	Mit-raExchangeCaller     // Read-only binding to the contract
	Mit-raExchangeTransactor // Write-only binding to the contract
	Mit-raExchangeFilterer   // Log filterer for contract events
}

// Mit-raExchangeCaller is an auto generated read-only Go binding around an Ethereum contract.
type Mit-raExchangeCaller struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// Mit-raExchangeTransactor is an auto generated write-only Go binding around an Ethereum contract.
type Mit-raExchangeTransactor struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// Mit-raExchangeFilterer is an auto generated log filtering Go binding around an Ethereum contract events.
type Mit-raExchangeFilterer struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// Mit-raExchangeSession is an auto generated Go binding around an Ethereum contract,
// with pre-set call and transact options.
type Mit-raExchangeSession struct {
	Contract     *Mit-raExchange     // Generic contract binding to set the session for
	CallOpts     bind.CallOpts     // Call options to use throughout this session
	TransactOpts bind.TransactOpts // Transaction auth options to use throughout this session
}

// Mit-raExchangeCallerSession is an auto generated read-only Go binding around an Ethereum contract,
// with pre-set call options.
type Mit-raExchangeCallerSession struct {
	Contract *Mit-raExchangeCaller // Generic contract caller binding to set the session for
	CallOpts bind.CallOpts       // Call options to use throughout this session
}

// Mit-raExchangeTransactorSession is an auto generated write-only Go binding around an Ethereum contract,
// with pre-set transact options.
type Mit-raExchangeTransactorSession struct {
	Contract     *Mit-raExchangeTransactor // Generic contract transactor binding to set the session for
	TransactOpts bind.TransactOpts       // Transaction auth options to use throughout this session
}

// Mit-raExchangeRaw is an auto generated low-level Go binding around an Ethereum contract.
type Mit-raExchangeRaw struct {
	Contract *Mit-raExchange // Generic contract binding to access the raw methods on
}

// Mit-raExchangeCallerRaw is an auto generated low-level read-only Go binding around an Ethereum contract.
type Mit-raExchangeCallerRaw struct {
	Contract *Mit-raExchangeCaller // Generic read-only contract binding to access the raw methods on
}

// Mit-raExchangeTransactorRaw is an auto generated low-level write-only Go binding around an Ethereum contract.
type Mit-raExchangeTransactorRaw struct {
	Contract *Mit-raExchangeTransactor // Generic write-only contract binding to access the raw methods on
}

// NewMit-raExchange creates a new instance of Mit-raExchange, bound to a specific deployed contract.
func NewMit-raExchange(address common.Address, backend bind.ContractBackend) (*Mit-raExchange, error) {
	contract, err := bindMit-raExchange(address, backend, backend, backend)
	if err != nil {
		return nil, err
	}
	return &Mit-raExchange{Mit-raExchangeCaller: Mit-raExchangeCaller{contract: contract}, Mit-raExchangeTransactor: Mit-raExchangeTransactor{contract: contract}, Mit-raExchangeFilterer: Mit-raExchangeFilterer{contract: contract}}, nil
}

// NewMit-raExchangeCaller creates a new read-only instance of Mit-raExchange, bound to a specific deployed contract.
func NewMit-raExchangeCaller(address common.Address, caller bind.ContractCaller) (*Mit-raExchangeCaller, error) {
	contract, err := bindMit-raExchange(address, caller, nil, nil)
	if err != nil {
		return nil, err
	}
	return &Mit-raExchangeCaller{contract: contract}, nil
}

// NewMit-raExchangeTransactor creates a new write-only instance of Mit-raExchange, bound to a specific deployed contract.
func NewMit-raExchangeTransactor(address common.Address, transactor bind.ContractTransactor) (*Mit-raExchangeTransactor, error) {
	contract, err := bindMit-raExchange(address, nil, transactor, nil)
	if err != nil {
		return nil, err
	}
	return &Mit-raExchangeTransactor{contract: contract}, nil
}

// NewMit-raExchangeFilterer creates a new log filterer instance of Mit-raExchange, bound to a specific deployed contract.
func NewMit-raExchangeFilterer(address common.Address, filterer bind.ContractFilterer) (*Mit-raExchangeFilterer, error) {
	contract, err := bindMit-raExchange(address, nil, nil, filterer)
	if err != nil {
		return nil, err
	}
	return &Mit-raExchangeFilterer{contract: contract}, nil
}

// bindMit-raExchange binds a generic wrapper to an already deployed contract.
func bindMit-raExchange(address common.Address, caller bind.ContractCaller, transactor bind.ContractTransactor, filterer bind.ContractFilterer) (*bind.BoundContract, error) {
	parsed, err := abi.JSON(strings.NewReader(Mit-raExchangeABI))
	if err != nil {
		return nil, err
	}
	return bind.NewBoundContract(address, parsed, caller, transactor, filterer), nil
}

// Call invokes the (constant) contract method with params as input values and
// sets the output to result. The result type might be a single field for simple
// returns, a slice of interfaces for anonymous returns and a struct for named
// returns.
func (_Mit-raExchange *Mit-raExchangeRaw) Call(opts *bind.CallOpts, result interface{}, method string, params ...interface{}) error {
	return _Mit-raExchange.Contract.Mit-raExchangeCaller.contract.Call(opts, result, method, params...)
}

// Transfer initiates a plain transaction to move funds to the contract, calling
// its default method if one is available.
func (_Mit-raExchange *Mit-raExchangeRaw) Transfer(opts *bind.TransactOpts) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.Mit-raExchangeTransactor.contract.Transfer(opts)
}

// Transact invokes the (paid) contract method with params as input values.
func (_Mit-raExchange *Mit-raExchangeRaw) Transact(opts *bind.TransactOpts, method string, params ...interface{}) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.Mit-raExchangeTransactor.contract.Transact(opts, method, params...)
}

// Call invokes the (constant) contract method with params as input values and
// sets the output to result. The result type might be a single field for simple
// returns, a slice of interfaces for anonymous returns and a struct for named
// returns.
func (_Mit-raExchange *Mit-raExchangeCallerRaw) Call(opts *bind.CallOpts, result interface{}, method string, params ...interface{}) error {
	return _Mit-raExchange.Contract.contract.Call(opts, result, method, params...)
}

// Transfer initiates a plain transaction to move funds to the contract, calling
// its default method if one is available.
func (_Mit-raExchange *Mit-raExchangeTransactorRaw) Transfer(opts *bind.TransactOpts) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.contract.Transfer(opts)
}

// Transact invokes the (paid) contract method with params as input values.
func (_Mit-raExchange *Mit-raExchangeTransactorRaw) Transact(opts *bind.TransactOpts, method string, params ...interface{}) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.contract.Transact(opts, method, params...)
}

// Coeff is a free data retrieval call binding the contract method 0x87b261ad.
//
// Solidity: function coeff() constant returns(address)
func (_Mit-raExchange *Mit-raExchangeCaller) Coeff(opts *bind.CallOpts) (common.Address, error) {
	var (
		ret0 = new(common.Address)
	)
	out := ret0
	err := _Mit-raExchange.contract.Call(opts, out, "coeff")
	return *ret0, err
}

// Coeff is a free data retrieval call binding the contract method 0x87b261ad.
//
// Solidity: function coeff() constant returns(address)
func (_Mit-raExchange *Mit-raExchangeSession) Coeff() (common.Address, error) {
	return _Mit-raExchange.Contract.Coeff(&_Mit-raExchange.CallOpts)
}

// Coeff is a free data retrieval call binding the contract method 0x87b261ad.
//
// Solidity: function coeff() constant returns(address)
func (_Mit-raExchange *Mit-raExchangeCallerSession) Coeff() (common.Address, error) {
	return _Mit-raExchange.Contract.Coeff(&_Mit-raExchange.CallOpts)
}

// GetAdSpaceCoeff is a free data retrieval call binding the contract method 0x45e09d88.
//
// Solidity: function getAdSpaceCoeff(id bytes16, index uint16) constant returns(int64)
func (_Mit-raExchange *Mit-raExchangeCaller) GetAdSpaceCoeff(opts *bind.CallOpts, id [16]byte, index uint16) (int64, error) {
	var (
		ret0 = new(int64)
	)
	out := ret0
	err := _Mit-raExchange.contract.Call(opts, out, "getAdSpaceCoeff", id, index)
	return *ret0, err
}

// GetAdSpaceCoeff is a free data retrieval call binding the contract method 0x45e09d88.
//
// Solidity: function getAdSpaceCoeff(id bytes16, index uint16) constant returns(int64)
func (_Mit-raExchange *Mit-raExchangeSession) GetAdSpaceCoeff(id [16]byte, index uint16) (int64, error) {
	return _Mit-raExchange.Contract.GetAdSpaceCoeff(&_Mit-raExchange.CallOpts, id, index)
}

// GetAdSpaceCoeff is a free data retrieval call binding the contract method 0x45e09d88.
//
// Solidity: function getAdSpaceCoeff(id bytes16, index uint16) constant returns(int64)
func (_Mit-raExchange *Mit-raExchangeCallerSession) GetAdSpaceCoeff(id [16]byte, index uint16) (int64, error) {
	return _Mit-raExchange.Contract.GetAdSpaceCoeff(&_Mit-raExchange.CallOpts, id, index)
}

// GetAdvertiserCoeff is a free data retrieval call binding the contract method 0x06e7bdb1.
//
// Solidity: function getAdvertiserCoeff(id bytes16, index uint16) constant returns(int64)
func (_Mit-raExchange *Mit-raExchangeCaller) GetAdvertiserCoeff(opts *bind.CallOpts, id [16]byte, index uint16) (int64, error) {
	var (
		ret0 = new(int64)
	)
	out := ret0
	err := _Mit-raExchange.contract.Call(opts, out, "getAdvertiserCoeff", id, index)
	return *ret0, err
}

// GetAdvertiserCoeff is a free data retrieval call binding the contract method 0x06e7bdb1.
//
// Solidity: function getAdvertiserCoeff(id bytes16, index uint16) constant returns(int64)
func (_Mit-raExchange *Mit-raExchangeSession) GetAdvertiserCoeff(id [16]byte, index uint16) (int64, error) {
	return _Mit-raExchange.Contract.GetAdvertiserCoeff(&_Mit-raExchange.CallOpts, id, index)
}

// GetAdvertiserCoeff is a free data retrieval call binding the contract method 0x06e7bdb1.
//
// Solidity: function getAdvertiserCoeff(id bytes16, index uint16) constant returns(int64)
func (_Mit-raExchange *Mit-raExchangeCallerSession) GetAdvertiserCoeff(id [16]byte, index uint16) (int64, error) {
	return _Mit-raExchange.Contract.GetAdvertiserCoeff(&_Mit-raExchange.CallOpts, id, index)
}

// GetOfferCoeff is a free data retrieval call binding the contract method 0x1c44f0a4.
//
// Solidity: function getOfferCoeff(id bytes16, index uint16) constant returns(int64)
func (_Mit-raExchange *Mit-raExchangeCaller) GetOfferCoeff(opts *bind.CallOpts, id [16]byte, index uint16) (int64, error) {
	var (
		ret0 = new(int64)
	)
	out := ret0
	err := _Mit-raExchange.contract.Call(opts, out, "getOfferCoeff", id, index)
	return *ret0, err
}

// GetOfferCoeff is a free data retrieval call binding the contract method 0x1c44f0a4.
//
// Solidity: function getOfferCoeff(id bytes16, index uint16) constant returns(int64)
func (_Mit-raExchange *Mit-raExchangeSession) GetOfferCoeff(id [16]byte, index uint16) (int64, error) {
	return _Mit-raExchange.Contract.GetOfferCoeff(&_Mit-raExchange.CallOpts, id, index)
}

// GetOfferCoeff is a free data retrieval call binding the contract method 0x1c44f0a4.
//
// Solidity: function getOfferCoeff(id bytes16, index uint16) constant returns(int64)
func (_Mit-raExchange *Mit-raExchangeCallerSession) GetOfferCoeff(id [16]byte, index uint16) (int64, error) {
	return _Mit-raExchange.Contract.GetOfferCoeff(&_Mit-raExchange.CallOpts, id, index)
}

// GetPublisherCoeff is a free data retrieval call binding the contract method 0xeaa9a800.
//
// Solidity: function getPublisherCoeff(id bytes16, index uint16) constant returns(int64)
func (_Mit-raExchange *Mit-raExchangeCaller) GetPublisherCoeff(opts *bind.CallOpts, id [16]byte, index uint16) (int64, error) {
	var (
		ret0 = new(int64)
	)
	out := ret0
	err := _Mit-raExchange.contract.Call(opts, out, "getPublisherCoeff", id, index)
	return *ret0, err
}

// GetPublisherCoeff is a free data retrieval call binding the contract method 0xeaa9a800.
//
// Solidity: function getPublisherCoeff(id bytes16, index uint16) constant returns(int64)
func (_Mit-raExchange *Mit-raExchangeSession) GetPublisherCoeff(id [16]byte, index uint16) (int64, error) {
	return _Mit-raExchange.Contract.GetPublisherCoeff(&_Mit-raExchange.CallOpts, id, index)
}

// GetPublisherCoeff is a free data retrieval call binding the contract method 0xeaa9a800.
//
// Solidity: function getPublisherCoeff(id bytes16, index uint16) constant returns(int64)
func (_Mit-raExchange *Mit-raExchangeCallerSession) GetPublisherCoeff(id [16]byte, index uint16) (int64, error) {
	return _Mit-raExchange.Contract.GetPublisherCoeff(&_Mit-raExchange.CallOpts, id, index)
}

// Store is a free data retrieval call binding the contract method 0x975057e7.
//
// Solidity: function store() constant returns(address)
func (_Mit-raExchange *Mit-raExchangeCaller) Store(opts *bind.CallOpts) (common.Address, error) {
	var (
		ret0 = new(common.Address)
	)
	out := ret0
	err := _Mit-raExchange.contract.Call(opts, out, "store")
	return *ret0, err
}

// Store is a free data retrieval call binding the contract method 0x975057e7.
//
// Solidity: function store() constant returns(address)
func (_Mit-raExchange *Mit-raExchangeSession) Store() (common.Address, error) {
	return _Mit-raExchange.Contract.Store(&_Mit-raExchange.CallOpts)
}

// Store is a free data retrieval call binding the contract method 0x975057e7.
//
// Solidity: function store() constant returns(address)
func (_Mit-raExchange *Mit-raExchangeCallerSession) Store() (common.Address, error) {
	return _Mit-raExchange.Contract.Store(&_Mit-raExchange.CallOpts)
}

// SystemOwner is a free data retrieval call binding the contract method 0x33779254.
//
// Solidity: function systemOwner() constant returns(address)
func (_Mit-raExchange *Mit-raExchangeCaller) SystemOwner(opts *bind.CallOpts) (common.Address, error) {
	var (
		ret0 = new(common.Address)
	)
	out := ret0
	err := _Mit-raExchange.contract.Call(opts, out, "systemOwner")
	return *ret0, err
}

// SystemOwner is a free data retrieval call binding the contract method 0x33779254.
//
// Solidity: function systemOwner() constant returns(address)
func (_Mit-raExchange *Mit-raExchangeSession) SystemOwner() (common.Address, error) {
	return _Mit-raExchange.Contract.SystemOwner(&_Mit-raExchange.CallOpts)
}

// SystemOwner is a free data retrieval call binding the contract method 0x33779254.
//
// Solidity: function systemOwner() constant returns(address)
func (_Mit-raExchange *Mit-raExchangeCallerSession) SystemOwner() (common.Address, error) {
	return _Mit-raExchange.Contract.SystemOwner(&_Mit-raExchange.CallOpts)
}

// CreateActionHit is a paid mutator transaction binding the contract method 0x01c1ba8d.
//
// Solidity: function createActionHit(id bytes16, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) CreateActionHit(opts *bind.TransactOpts, id [16]byte, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "createActionHit", id, session, space, offer, amount, details, categories, state)
}

// CreateActionHit is a paid mutator transaction binding the contract method 0x01c1ba8d.
//
// Solidity: function createActionHit(id bytes16, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeSession) CreateActionHit(id [16]byte, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.CreateActionHit(&_Mit-raExchange.TransactOpts, id, session, space, offer, amount, details, categories, state)
}

// CreateActionHit is a paid mutator transaction binding the contract method 0x01c1ba8d.
//
// Solidity: function createActionHit(id bytes16, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) CreateActionHit(id [16]byte, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.CreateActionHit(&_Mit-raExchange.TransactOpts, id, session, space, offer, amount, details, categories, state)
}

// CreateAdSpace is a paid mutator transaction binding the contract method 0xfaa1cd36.
//
// Solidity: function createAdSpace(id bytes16, owner bytes16, name string, url string, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) CreateAdSpace(opts *bind.TransactOpts, id [16]byte, owner [16]byte, name string, url string, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "createAdSpace", id, owner, name, url, details, categories, state)
}

// CreateAdSpace is a paid mutator transaction binding the contract method 0xfaa1cd36.
//
// Solidity: function createAdSpace(id bytes16, owner bytes16, name string, url string, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeSession) CreateAdSpace(id [16]byte, owner [16]byte, name string, url string, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.CreateAdSpace(&_Mit-raExchange.TransactOpts, id, owner, name, url, details, categories, state)
}

// CreateAdSpace is a paid mutator transaction binding the contract method 0xfaa1cd36.
//
// Solidity: function createAdSpace(id bytes16, owner bytes16, name string, url string, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) CreateAdSpace(id [16]byte, owner [16]byte, name string, url string, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.CreateAdSpace(&_Mit-raExchange.TransactOpts, id, owner, name, url, details, categories, state)
}

// CreateAdvertiser is a paid mutator transaction binding the contract method 0x41837e17.
//
// Solidity: function createAdvertiser(id bytes16, owner address, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) CreateAdvertiser(opts *bind.TransactOpts, id [16]byte, owner common.Address, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "createAdvertiser", id, owner, name, details, rank, state)
}

// CreateAdvertiser is a paid mutator transaction binding the contract method 0x41837e17.
//
// Solidity: function createAdvertiser(id bytes16, owner address, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeSession) CreateAdvertiser(id [16]byte, owner common.Address, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.CreateAdvertiser(&_Mit-raExchange.TransactOpts, id, owner, name, details, rank, state)
}

// CreateAdvertiser is a paid mutator transaction binding the contract method 0x41837e17.
//
// Solidity: function createAdvertiser(id bytes16, owner address, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) CreateAdvertiser(id [16]byte, owner common.Address, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.CreateAdvertiser(&_Mit-raExchange.TransactOpts, id, owner, name, details, rank, state)
}

// CreateDisplayHit is a paid mutator transaction binding the contract method 0xfd0dec48.
//
// Solidity: function createDisplayHit(id bytes16, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) CreateDisplayHit(opts *bind.TransactOpts, id [16]byte, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "createDisplayHit", id, session, space, offer, amount, details, categories, state)
}

// CreateDisplayHit is a paid mutator transaction binding the contract method 0xfd0dec48.
//
// Solidity: function createDisplayHit(id bytes16, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeSession) CreateDisplayHit(id [16]byte, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.CreateDisplayHit(&_Mit-raExchange.TransactOpts, id, session, space, offer, amount, details, categories, state)
}

// CreateDisplayHit is a paid mutator transaction binding the contract method 0xfd0dec48.
//
// Solidity: function createDisplayHit(id bytes16, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) CreateDisplayHit(id [16]byte, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.CreateDisplayHit(&_Mit-raExchange.TransactOpts, id, session, space, offer, amount, details, categories, state)
}

// CreateOffer is a paid mutator transaction binding the contract method 0x2f8ef80f.
//
// Solidity: function createOffer(id bytes16, owner bytes16, name string, hitPrice uint256, actionPrice uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) CreateOffer(opts *bind.TransactOpts, id [16]byte, owner [16]byte, name string, hitPrice *big.Int, actionPrice *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "createOffer", id, owner, name, hitPrice, actionPrice, details, categories, state)
}

// CreateOffer is a paid mutator transaction binding the contract method 0x2f8ef80f.
//
// Solidity: function createOffer(id bytes16, owner bytes16, name string, hitPrice uint256, actionPrice uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeSession) CreateOffer(id [16]byte, owner [16]byte, name string, hitPrice *big.Int, actionPrice *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.CreateOffer(&_Mit-raExchange.TransactOpts, id, owner, name, hitPrice, actionPrice, details, categories, state)
}

// CreateOffer is a paid mutator transaction binding the contract method 0x2f8ef80f.
//
// Solidity: function createOffer(id bytes16, owner bytes16, name string, hitPrice uint256, actionPrice uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) CreateOffer(id [16]byte, owner [16]byte, name string, hitPrice *big.Int, actionPrice *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.CreateOffer(&_Mit-raExchange.TransactOpts, id, owner, name, hitPrice, actionPrice, details, categories, state)
}

// CreatePublisher is a paid mutator transaction binding the contract method 0xa3392417.
//
// Solidity: function createPublisher(id bytes16, owner address, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) CreatePublisher(opts *bind.TransactOpts, id [16]byte, owner common.Address, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "createPublisher", id, owner, name, details, rank, state)
}

// CreatePublisher is a paid mutator transaction binding the contract method 0xa3392417.
//
// Solidity: function createPublisher(id bytes16, owner address, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeSession) CreatePublisher(id [16]byte, owner common.Address, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.CreatePublisher(&_Mit-raExchange.TransactOpts, id, owner, name, details, rank, state)
}

// CreatePublisher is a paid mutator transaction binding the contract method 0xa3392417.
//
// Solidity: function createPublisher(id bytes16, owner address, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) CreatePublisher(id [16]byte, owner common.Address, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.CreatePublisher(&_Mit-raExchange.TransactOpts, id, owner, name, details, rank, state)
}

// SetAdSpaceCoeffs is a paid mutator transaction binding the contract method 0xfa362e79.
//
// Solidity: function setAdSpaceCoeffs(id bytes16, coeffs int64[]) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) SetAdSpaceCoeffs(opts *bind.TransactOpts, id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "setAdSpaceCoeffs", id, coeffs)
}

// SetAdSpaceCoeffs is a paid mutator transaction binding the contract method 0xfa362e79.
//
// Solidity: function setAdSpaceCoeffs(id bytes16, coeffs int64[]) returns()
func (_Mit-raExchange *Mit-raExchangeSession) SetAdSpaceCoeffs(id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetAdSpaceCoeffs(&_Mit-raExchange.TransactOpts, id, coeffs)
}

// SetAdSpaceCoeffs is a paid mutator transaction binding the contract method 0xfa362e79.
//
// Solidity: function setAdSpaceCoeffs(id bytes16, coeffs int64[]) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) SetAdSpaceCoeffs(id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetAdSpaceCoeffs(&_Mit-raExchange.TransactOpts, id, coeffs)
}

// SetAdvertiserCoeffs is a paid mutator transaction binding the contract method 0x0c2bf561.
//
// Solidity: function setAdvertiserCoeffs(id bytes16, coeffs int64[]) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) SetAdvertiserCoeffs(opts *bind.TransactOpts, id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "setAdvertiserCoeffs", id, coeffs)
}

// SetAdvertiserCoeffs is a paid mutator transaction binding the contract method 0x0c2bf561.
//
// Solidity: function setAdvertiserCoeffs(id bytes16, coeffs int64[]) returns()
func (_Mit-raExchange *Mit-raExchangeSession) SetAdvertiserCoeffs(id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetAdvertiserCoeffs(&_Mit-raExchange.TransactOpts, id, coeffs)
}

// SetAdvertiserCoeffs is a paid mutator transaction binding the contract method 0x0c2bf561.
//
// Solidity: function setAdvertiserCoeffs(id bytes16, coeffs int64[]) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) SetAdvertiserCoeffs(id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetAdvertiserCoeffs(&_Mit-raExchange.TransactOpts, id, coeffs)
}

// SetCoeffAddress is a paid mutator transaction binding the contract method 0x9dd8a106.
//
// Solidity: function setCoeffAddress(coeffAddress address) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) SetCoeffAddress(opts *bind.TransactOpts, coeffAddress common.Address) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "setCoeffAddress", coeffAddress)
}

// SetCoeffAddress is a paid mutator transaction binding the contract method 0x9dd8a106.
//
// Solidity: function setCoeffAddress(coeffAddress address) returns()
func (_Mit-raExchange *Mit-raExchangeSession) SetCoeffAddress(coeffAddress common.Address) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetCoeffAddress(&_Mit-raExchange.TransactOpts, coeffAddress)
}

// SetCoeffAddress is a paid mutator transaction binding the contract method 0x9dd8a106.
//
// Solidity: function setCoeffAddress(coeffAddress address) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) SetCoeffAddress(coeffAddress common.Address) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetCoeffAddress(&_Mit-raExchange.TransactOpts, coeffAddress)
}

// SetOfferCoeffs is a paid mutator transaction binding the contract method 0xe1df6035.
//
// Solidity: function setOfferCoeffs(id bytes16, coeffs int64[]) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) SetOfferCoeffs(opts *bind.TransactOpts, id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "setOfferCoeffs", id, coeffs)
}

// SetOfferCoeffs is a paid mutator transaction binding the contract method 0xe1df6035.
//
// Solidity: function setOfferCoeffs(id bytes16, coeffs int64[]) returns()
func (_Mit-raExchange *Mit-raExchangeSession) SetOfferCoeffs(id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetOfferCoeffs(&_Mit-raExchange.TransactOpts, id, coeffs)
}

// SetOfferCoeffs is a paid mutator transaction binding the contract method 0xe1df6035.
//
// Solidity: function setOfferCoeffs(id bytes16, coeffs int64[]) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) SetOfferCoeffs(id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetOfferCoeffs(&_Mit-raExchange.TransactOpts, id, coeffs)
}

// SetPublisherCoeffs is a paid mutator transaction binding the contract method 0x895b5111.
//
// Solidity: function setPublisherCoeffs(id bytes16, coeffs int64[]) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) SetPublisherCoeffs(opts *bind.TransactOpts, id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "setPublisherCoeffs", id, coeffs)
}

// SetPublisherCoeffs is a paid mutator transaction binding the contract method 0x895b5111.
//
// Solidity: function setPublisherCoeffs(id bytes16, coeffs int64[]) returns()
func (_Mit-raExchange *Mit-raExchangeSession) SetPublisherCoeffs(id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetPublisherCoeffs(&_Mit-raExchange.TransactOpts, id, coeffs)
}

// SetPublisherCoeffs is a paid mutator transaction binding the contract method 0x895b5111.
//
// Solidity: function setPublisherCoeffs(id bytes16, coeffs int64[]) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) SetPublisherCoeffs(id [16]byte, coeffs []int64) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetPublisherCoeffs(&_Mit-raExchange.TransactOpts, id, coeffs)
}

// SetStorageAddress is a paid mutator transaction binding the contract method 0x59b910d6.
//
// Solidity: function setStorageAddress(storageAddress address) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) SetStorageAddress(opts *bind.TransactOpts, storageAddress common.Address) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "setStorageAddress", storageAddress)
}

// SetStorageAddress is a paid mutator transaction binding the contract method 0x59b910d6.
//
// Solidity: function setStorageAddress(storageAddress address) returns()
func (_Mit-raExchange *Mit-raExchangeSession) SetStorageAddress(storageAddress common.Address) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetStorageAddress(&_Mit-raExchange.TransactOpts, storageAddress)
}

// SetStorageAddress is a paid mutator transaction binding the contract method 0x59b910d6.
//
// Solidity: function setStorageAddress(storageAddress address) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) SetStorageAddress(storageAddress common.Address) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetStorageAddress(&_Mit-raExchange.TransactOpts, storageAddress)
}

// SetSystemOwner is a paid mutator transaction binding the contract method 0x621eb9a2.
//
// Solidity: function setSystemOwner(systemOwnerAddress address) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) SetSystemOwner(opts *bind.TransactOpts, systemOwnerAddress common.Address) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "setSystemOwner", systemOwnerAddress)
}

// SetSystemOwner is a paid mutator transaction binding the contract method 0x621eb9a2.
//
// Solidity: function setSystemOwner(systemOwnerAddress address) returns()
func (_Mit-raExchange *Mit-raExchangeSession) SetSystemOwner(systemOwnerAddress common.Address) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetSystemOwner(&_Mit-raExchange.TransactOpts, systemOwnerAddress)
}

// SetSystemOwner is a paid mutator transaction binding the contract method 0x621eb9a2.
//
// Solidity: function setSystemOwner(systemOwnerAddress address) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) SetSystemOwner(systemOwnerAddress common.Address) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.SetSystemOwner(&_Mit-raExchange.TransactOpts, systemOwnerAddress)
}

// TransactHit is a paid mutator transaction binding the contract method 0xdfc3cfca.
//
// Solidity: function transactHit(id bytes16, amount uint256) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) TransactHit(opts *bind.TransactOpts, id [16]byte, amount *big.Int) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "transactHit", id, amount)
}

// TransactHit is a paid mutator transaction binding the contract method 0xdfc3cfca.
//
// Solidity: function transactHit(id bytes16, amount uint256) returns()
func (_Mit-raExchange *Mit-raExchangeSession) TransactHit(id [16]byte, amount *big.Int) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.TransactHit(&_Mit-raExchange.TransactOpts, id, amount)
}

// TransactHit is a paid mutator transaction binding the contract method 0xdfc3cfca.
//
// Solidity: function transactHit(id bytes16, amount uint256) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) TransactHit(id [16]byte, amount *big.Int) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.TransactHit(&_Mit-raExchange.TransactOpts, id, amount)
}

// UpdateActionHit is a paid mutator transaction binding the contract method 0x8363d03d.
//
// Solidity: function updateActionHit(id bytes16, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) UpdateActionHit(opts *bind.TransactOpts, id [16]byte, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "updateActionHit", id, session, space, offer, amount, details, categories, state)
}

// UpdateActionHit is a paid mutator transaction binding the contract method 0x8363d03d.
//
// Solidity: function updateActionHit(id bytes16, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeSession) UpdateActionHit(id [16]byte, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.UpdateActionHit(&_Mit-raExchange.TransactOpts, id, session, space, offer, amount, details, categories, state)
}

// UpdateActionHit is a paid mutator transaction binding the contract method 0x8363d03d.
//
// Solidity: function updateActionHit(id bytes16, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) UpdateActionHit(id [16]byte, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.UpdateActionHit(&_Mit-raExchange.TransactOpts, id, session, space, offer, amount, details, categories, state)
}

// UpdateAdSpace is a paid mutator transaction binding the contract method 0x48047f00.
//
// Solidity: function updateAdSpace(id bytes16, owner bytes16, name string, url string, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) UpdateAdSpace(opts *bind.TransactOpts, id [16]byte, owner [16]byte, name string, url string, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "updateAdSpace", id, owner, name, url, details, categories, state)
}

// UpdateAdSpace is a paid mutator transaction binding the contract method 0x48047f00.
//
// Solidity: function updateAdSpace(id bytes16, owner bytes16, name string, url string, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeSession) UpdateAdSpace(id [16]byte, owner [16]byte, name string, url string, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.UpdateAdSpace(&_Mit-raExchange.TransactOpts, id, owner, name, url, details, categories, state)
}

// UpdateAdSpace is a paid mutator transaction binding the contract method 0x48047f00.
//
// Solidity: function updateAdSpace(id bytes16, owner bytes16, name string, url string, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) UpdateAdSpace(id [16]byte, owner [16]byte, name string, url string, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.UpdateAdSpace(&_Mit-raExchange.TransactOpts, id, owner, name, url, details, categories, state)
}

// UpdateAdvertiser is a paid mutator transaction binding the contract method 0x8ed752df.
//
// Solidity: function updateAdvertiser(id bytes16, owner address, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) UpdateAdvertiser(opts *bind.TransactOpts, id [16]byte, owner common.Address, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "updateAdvertiser", id, owner, name, details, rank, state)
}

// UpdateAdvertiser is a paid mutator transaction binding the contract method 0x8ed752df.
//
// Solidity: function updateAdvertiser(id bytes16, owner address, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeSession) UpdateAdvertiser(id [16]byte, owner common.Address, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.UpdateAdvertiser(&_Mit-raExchange.TransactOpts, id, owner, name, details, rank, state)
}

// UpdateAdvertiser is a paid mutator transaction binding the contract method 0x8ed752df.
//
// Solidity: function updateAdvertiser(id bytes16, owner address, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) UpdateAdvertiser(id [16]byte, owner common.Address, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.UpdateAdvertiser(&_Mit-raExchange.TransactOpts, id, owner, name, details, rank, state)
}

// UpdateDisplayHit is a paid mutator transaction binding the contract method 0xbde170d4.
//
// Solidity: function updateDisplayHit(id bytes16, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) UpdateDisplayHit(opts *bind.TransactOpts, id [16]byte, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "updateDisplayHit", id, session, space, offer, amount, details, categories, state)
}

// UpdateDisplayHit is a paid mutator transaction binding the contract method 0xbde170d4.
//
// Solidity: function updateDisplayHit(id bytes16, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeSession) UpdateDisplayHit(id [16]byte, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.UpdateDisplayHit(&_Mit-raExchange.TransactOpts, id, session, space, offer, amount, details, categories, state)
}

// UpdateDisplayHit is a paid mutator transaction binding the contract method 0xbde170d4.
//
// Solidity: function updateDisplayHit(id bytes16, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) UpdateDisplayHit(id [16]byte, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.UpdateDisplayHit(&_Mit-raExchange.TransactOpts, id, session, space, offer, amount, details, categories, state)
}

// UpdateOffer is a paid mutator transaction binding the contract method 0xc50c53f4.
//
// Solidity: function updateOffer(id bytes16, owner bytes16, name string, hitPrice uint256, actionPrice uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) UpdateOffer(opts *bind.TransactOpts, id [16]byte, owner [16]byte, name string, hitPrice *big.Int, actionPrice *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "updateOffer", id, owner, name, hitPrice, actionPrice, details, categories, state)
}

// UpdateOffer is a paid mutator transaction binding the contract method 0xc50c53f4.
//
// Solidity: function updateOffer(id bytes16, owner bytes16, name string, hitPrice uint256, actionPrice uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeSession) UpdateOffer(id [16]byte, owner [16]byte, name string, hitPrice *big.Int, actionPrice *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.UpdateOffer(&_Mit-raExchange.TransactOpts, id, owner, name, hitPrice, actionPrice, details, categories, state)
}

// UpdateOffer is a paid mutator transaction binding the contract method 0xc50c53f4.
//
// Solidity: function updateOffer(id bytes16, owner bytes16, name string, hitPrice uint256, actionPrice uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) UpdateOffer(id [16]byte, owner [16]byte, name string, hitPrice *big.Int, actionPrice *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.UpdateOffer(&_Mit-raExchange.TransactOpts, id, owner, name, hitPrice, actionPrice, details, categories, state)
}

// UpdatePublisher is a paid mutator transaction binding the contract method 0xaa569e50.
//
// Solidity: function updatePublisher(id bytes16, owner address, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactor) UpdatePublisher(opts *bind.TransactOpts, id [16]byte, owner common.Address, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.contract.Transact(opts, "updatePublisher", id, owner, name, details, rank, state)
}

// UpdatePublisher is a paid mutator transaction binding the contract method 0xaa569e50.
//
// Solidity: function updatePublisher(id bytes16, owner address, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeSession) UpdatePublisher(id [16]byte, owner common.Address, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.UpdatePublisher(&_Mit-raExchange.TransactOpts, id, owner, name, details, rank, state)
}

// UpdatePublisher is a paid mutator transaction binding the contract method 0xaa569e50.
//
// Solidity: function updatePublisher(id bytes16, owner address, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raExchange *Mit-raExchangeTransactorSession) UpdatePublisher(id [16]byte, owner common.Address, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raExchange.Contract.UpdatePublisher(&_Mit-raExchange.TransactOpts, id, owner, name, details, rank, state)
}

// Mit-raExchangeAdSpaceCreatedIterator is returned from FilterAdSpaceCreated and is used to iterate over the raw logs and unpacked data for AdSpaceCreated events raised by the Mit-raExchange contract.
type Mit-raExchangeAdSpaceCreatedIterator struct {
	Event *Mit-raExchangeAdSpaceCreated // Event containing the contract specifics and raw log

	contract *bind.BoundContract // Generic contract to use for unpacking event data
	event    string              // Event name to use for unpacking event data

	logs chan types.Log        // Log channel receiving the found contract events
	sub  ethereum.Subscription // Subscription for errors, completion and termination
	done bool                  // Whether the subscription completed delivering logs
	fail error                 // Occurred error to stop iteration
}

// Next advances the iterator to the subsequent event, returning whether there
// are any more events found. In case of a retrieval or parsing error, false is
// returned and Error() can be queried for the exact failure.
func (it *Mit-raExchangeAdSpaceCreatedIterator) Next() bool {
	// If the iterator failed, stop iterating
	if it.fail != nil {
		return false
	}
	// If the iterator completed, deliver directly whatever's available
	if it.done {
		select {
		case log := <-it.logs:
			it.Event = new(Mit-raExchangeAdSpaceCreated)
			if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
				it.fail = err
				return false
			}
			it.Event.Raw = log
			return true

		default:
			return false
		}
	}
	// Iterator still in progress, wait for either a data or an error event
	select {
	case log := <-it.logs:
		it.Event = new(Mit-raExchangeAdSpaceCreated)
		if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
			it.fail = err
			return false
		}
		it.Event.Raw = log
		return true

	case err := <-it.sub.Err():
		it.done = true
		it.fail = err
		return it.Next()
	}
}

// Error returns any retrieval or parsing error occurred during filtering.
func (it *Mit-raExchangeAdSpaceCreatedIterator) Error() error {
	return it.fail
}

// Close terminates the iteration process, releasing any pending underlying
// resources.
func (it *Mit-raExchangeAdSpaceCreatedIterator) Close() error {
	it.sub.Unsubscribe()
	return nil
}

// Mit-raExchangeAdSpaceCreated represents a AdSpaceCreated event raised by the Mit-raExchange contract.
type Mit-raExchangeAdSpaceCreated struct {
	Id    [16]byte
	Owner [16]byte
	Raw   types.Log // Blockchain specific contextual infos
}

// FilterAdSpaceCreated is a free log retrieval operation binding the contract event 0x49356dee5ff51d2c6badbfa96d72bbe12dd742c52ea5b1f9a8a52afb92c54d18.
//
// Solidity: event AdSpaceCreated(id indexed bytes16, owner indexed bytes16)
func (_Mit-raExchange *Mit-raExchangeFilterer) FilterAdSpaceCreated(opts *bind.FilterOpts, id [][16]byte, owner [][16]byte) (*Mit-raExchangeAdSpaceCreatedIterator, error) {

	var idRule []interface{}
	for _, idItem := range id {
		idRule = append(idRule, idItem)
	}
	var ownerRule []interface{}
	for _, ownerItem := range owner {
		ownerRule = append(ownerRule, ownerItem)
	}

	logs, sub, err := _Mit-raExchange.contract.FilterLogs(opts, "AdSpaceCreated", idRule, ownerRule)
	if err != nil {
		return nil, err
	}
	return &Mit-raExchangeAdSpaceCreatedIterator{contract: _Mit-raExchange.contract, event: "AdSpaceCreated", logs: logs, sub: sub}, nil
}

// WatchAdSpaceCreated is a free log subscription operation binding the contract event 0x49356dee5ff51d2c6badbfa96d72bbe12dd742c52ea5b1f9a8a52afb92c54d18.
//
// Solidity: event AdSpaceCreated(id indexed bytes16, owner indexed bytes16)
func (_Mit-raExchange *Mit-raExchangeFilterer) WatchAdSpaceCreated(opts *bind.WatchOpts, sink chan<- *Mit-raExchangeAdSpaceCreated, id [][16]byte, owner [][16]byte) (event.Subscription, error) {

	var idRule []interface{}
	for _, idItem := range id {
		idRule = append(idRule, idItem)
	}
	var ownerRule []interface{}
	for _, ownerItem := range owner {
		ownerRule = append(ownerRule, ownerItem)
	}

	logs, sub, err := _Mit-raExchange.contract.WatchLogs(opts, "AdSpaceCreated", idRule, ownerRule)
	if err != nil {
		return nil, err
	}
	return event.NewSubscription(func(quit <-chan struct{}) error {
		defer sub.Unsubscribe()
		for {
			select {
			case log := <-logs:
				// New log arrived, parse the event and forward to the user
				event := new(Mit-raExchangeAdSpaceCreated)
				if err := _Mit-raExchange.contract.UnpackLog(event, "AdSpaceCreated", log); err != nil {
					return err
				}
				event.Raw = log

				select {
				case sink <- event:
				case err := <-sub.Err():
					return err
				case <-quit:
					return nil
				}
			case err := <-sub.Err():
				return err
			case <-quit:
				return nil
			}
		}
	}), nil
}

// Mit-raExchangeAdvertiserCreatedIterator is returned from FilterAdvertiserCreated and is used to iterate over the raw logs and unpacked data for AdvertiserCreated events raised by the Mit-raExchange contract.
type Mit-raExchangeAdvertiserCreatedIterator struct {
	Event *Mit-raExchangeAdvertiserCreated // Event containing the contract specifics and raw log

	contract *bind.BoundContract // Generic contract to use for unpacking event data
	event    string              // Event name to use for unpacking event data

	logs chan types.Log        // Log channel receiving the found contract events
	sub  ethereum.Subscription // Subscription for errors, completion and termination
	done bool                  // Whether the subscription completed delivering logs
	fail error                 // Occurred error to stop iteration
}

// Next advances the iterator to the subsequent event, returning whether there
// are any more events found. In case of a retrieval or parsing error, false is
// returned and Error() can be queried for the exact failure.
func (it *Mit-raExchangeAdvertiserCreatedIterator) Next() bool {
	// If the iterator failed, stop iterating
	if it.fail != nil {
		return false
	}
	// If the iterator completed, deliver directly whatever's available
	if it.done {
		select {
		case log := <-it.logs:
			it.Event = new(Mit-raExchangeAdvertiserCreated)
			if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
				it.fail = err
				return false
			}
			it.Event.Raw = log
			return true

		default:
			return false
		}
	}
	// Iterator still in progress, wait for either a data or an error event
	select {
	case log := <-it.logs:
		it.Event = new(Mit-raExchangeAdvertiserCreated)
		if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
			it.fail = err
			return false
		}
		it.Event.Raw = log
		return true

	case err := <-it.sub.Err():
		it.done = true
		it.fail = err
		return it.Next()
	}
}

// Error returns any retrieval or parsing error occurred during filtering.
func (it *Mit-raExchangeAdvertiserCreatedIterator) Error() error {
	return it.fail
}

// Close terminates the iteration process, releasing any pending underlying
// resources.
func (it *Mit-raExchangeAdvertiserCreatedIterator) Close() error {
	it.sub.Unsubscribe()
	return nil
}

// Mit-raExchangeAdvertiserCreated represents a AdvertiserCreated event raised by the Mit-raExchange contract.
type Mit-raExchangeAdvertiserCreated struct {
	Id    [16]byte
	Owner common.Address
	Raw   types.Log // Blockchain specific contextual infos
}

// FilterAdvertiserCreated is a free log retrieval operation binding the contract event 0xc1d8ed79dee2680263f53981ac2d751cebe1536ff6933bb06f28769e54b6c49a.
//
// Solidity: event AdvertiserCreated(id indexed bytes16, owner indexed address)
func (_Mit-raExchange *Mit-raExchangeFilterer) FilterAdvertiserCreated(opts *bind.FilterOpts, id [][16]byte, owner []common.Address) (*Mit-raExchangeAdvertiserCreatedIterator, error) {

	var idRule []interface{}
	for _, idItem := range id {
		idRule = append(idRule, idItem)
	}
	var ownerRule []interface{}
	for _, ownerItem := range owner {
		ownerRule = append(ownerRule, ownerItem)
	}

	logs, sub, err := _Mit-raExchange.contract.FilterLogs(opts, "AdvertiserCreated", idRule, ownerRule)
	if err != nil {
		return nil, err
	}
	return &Mit-raExchangeAdvertiserCreatedIterator{contract: _Mit-raExchange.contract, event: "AdvertiserCreated", logs: logs, sub: sub}, nil
}

// WatchAdvertiserCreated is a free log subscription operation binding the contract event 0xc1d8ed79dee2680263f53981ac2d751cebe1536ff6933bb06f28769e54b6c49a.
//
// Solidity: event AdvertiserCreated(id indexed bytes16, owner indexed address)
func (_Mit-raExchange *Mit-raExchangeFilterer) WatchAdvertiserCreated(opts *bind.WatchOpts, sink chan<- *Mit-raExchangeAdvertiserCreated, id [][16]byte, owner []common.Address) (event.Subscription, error) {

	var idRule []interface{}
	for _, idItem := range id {
		idRule = append(idRule, idItem)
	}
	var ownerRule []interface{}
	for _, ownerItem := range owner {
		ownerRule = append(ownerRule, ownerItem)
	}

	logs, sub, err := _Mit-raExchange.contract.WatchLogs(opts, "AdvertiserCreated", idRule, ownerRule)
	if err != nil {
		return nil, err
	}
	return event.NewSubscription(func(quit <-chan struct{}) error {
		defer sub.Unsubscribe()
		for {
			select {
			case log := <-logs:
				// New log arrived, parse the event and forward to the user
				event := new(Mit-raExchangeAdvertiserCreated)
				if err := _Mit-raExchange.contract.UnpackLog(event, "AdvertiserCreated", log); err != nil {
					return err
				}
				event.Raw = log

				select {
				case sink <- event:
				case err := <-sub.Err():
					return err
				case <-quit:
					return nil
				}
			case err := <-sub.Err():
				return err
			case <-quit:
				return nil
			}
		}
	}), nil
}

// Mit-raExchangeHitCreatedIterator is returned from FilterHitCreated and is used to iterate over the raw logs and unpacked data for HitCreated events raised by the Mit-raExchange contract.
type Mit-raExchangeHitCreatedIterator struct {
	Event *Mit-raExchangeHitCreated // Event containing the contract specifics and raw log

	contract *bind.BoundContract // Generic contract to use for unpacking event data
	event    string              // Event name to use for unpacking event data

	logs chan types.Log        // Log channel receiving the found contract events
	sub  ethereum.Subscription // Subscription for errors, completion and termination
	done bool                  // Whether the subscription completed delivering logs
	fail error                 // Occurred error to stop iteration
}

// Next advances the iterator to the subsequent event, returning whether there
// are any more events found. In case of a retrieval or parsing error, false is
// returned and Error() can be queried for the exact failure.
func (it *Mit-raExchangeHitCreatedIterator) Next() bool {
	// If the iterator failed, stop iterating
	if it.fail != nil {
		return false
	}
	// If the iterator completed, deliver directly whatever's available
	if it.done {
		select {
		case log := <-it.logs:
			it.Event = new(Mit-raExchangeHitCreated)
			if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
				it.fail = err
				return false
			}
			it.Event.Raw = log
			return true

		default:
			return false
		}
	}
	// Iterator still in progress, wait for either a data or an error event
	select {
	case log := <-it.logs:
		it.Event = new(Mit-raExchangeHitCreated)
		if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
			it.fail = err
			return false
		}
		it.Event.Raw = log
		return true

	case err := <-it.sub.Err():
		it.done = true
		it.fail = err
		return it.Next()
	}
}

// Error returns any retrieval or parsing error occurred during filtering.
func (it *Mit-raExchangeHitCreatedIterator) Error() error {
	return it.fail
}

// Close terminates the iteration process, releasing any pending underlying
// resources.
func (it *Mit-raExchangeHitCreatedIterator) Close() error {
	it.sub.Unsubscribe()
	return nil
}

// Mit-raExchangeHitCreated represents a HitCreated event raised by the Mit-raExchange contract.
type Mit-raExchangeHitCreated struct {
	Id     [16]byte
	Offer  [16]byte
	Amount *big.Int
	Raw    types.Log // Blockchain specific contextual infos
}

// FilterHitCreated is a free log retrieval operation binding the contract event 0xb1ed61a63a8c9a4a24619a622cfb89000d005cbdd391a707fcc292ba57c1fb63.
//
// Solidity: event HitCreated(id indexed bytes16, offer indexed bytes16, amount uint256)
func (_Mit-raExchange *Mit-raExchangeFilterer) FilterHitCreated(opts *bind.FilterOpts, id [][16]byte, offer [][16]byte) (*Mit-raExchangeHitCreatedIterator, error) {

	var idRule []interface{}
	for _, idItem := range id {
		idRule = append(idRule, idItem)
	}
	var offerRule []interface{}
	for _, offerItem := range offer {
		offerRule = append(offerRule, offerItem)
	}

	logs, sub, err := _Mit-raExchange.contract.FilterLogs(opts, "HitCreated", idRule, offerRule)
	if err != nil {
		return nil, err
	}
	return &Mit-raExchangeHitCreatedIterator{contract: _Mit-raExchange.contract, event: "HitCreated", logs: logs, sub: sub}, nil
}

// WatchHitCreated is a free log subscription operation binding the contract event 0xb1ed61a63a8c9a4a24619a622cfb89000d005cbdd391a707fcc292ba57c1fb63.
//
// Solidity: event HitCreated(id indexed bytes16, offer indexed bytes16, amount uint256)
func (_Mit-raExchange *Mit-raExchangeFilterer) WatchHitCreated(opts *bind.WatchOpts, sink chan<- *Mit-raExchangeHitCreated, id [][16]byte, offer [][16]byte) (event.Subscription, error) {

	var idRule []interface{}
	for _, idItem := range id {
		idRule = append(idRule, idItem)
	}
	var offerRule []interface{}
	for _, offerItem := range offer {
		offerRule = append(offerRule, offerItem)
	}

	logs, sub, err := _Mit-raExchange.contract.WatchLogs(opts, "HitCreated", idRule, offerRule)
	if err != nil {
		return nil, err
	}
	return event.NewSubscription(func(quit <-chan struct{}) error {
		defer sub.Unsubscribe()
		for {
			select {
			case log := <-logs:
				// New log arrived, parse the event and forward to the user
				event := new(Mit-raExchangeHitCreated)
				if err := _Mit-raExchange.contract.UnpackLog(event, "HitCreated", log); err != nil {
					return err
				}
				event.Raw = log

				select {
				case sink <- event:
				case err := <-sub.Err():
					return err
				case <-quit:
					return nil
				}
			case err := <-sub.Err():
				return err
			case <-quit:
				return nil
			}
		}
	}), nil
}

// Mit-raExchangeHitTransactedIterator is returned from FilterHitTransacted and is used to iterate over the raw logs and unpacked data for HitTransacted events raised by the Mit-raExchange contract.
type Mit-raExchangeHitTransactedIterator struct {
	Event *Mit-raExchangeHitTransacted // Event containing the contract specifics and raw log

	contract *bind.BoundContract // Generic contract to use for unpacking event data
	event    string              // Event name to use for unpacking event data

	logs chan types.Log        // Log channel receiving the found contract events
	sub  ethereum.Subscription // Subscription for errors, completion and termination
	done bool                  // Whether the subscription completed delivering logs
	fail error                 // Occurred error to stop iteration
}

// Next advances the iterator to the subsequent event, returning whether there
// are any more events found. In case of a retrieval or parsing error, false is
// returned and Error() can be queried for the exact failure.
func (it *Mit-raExchangeHitTransactedIterator) Next() bool {
	// If the iterator failed, stop iterating
	if it.fail != nil {
		return false
	}
	// If the iterator completed, deliver directly whatever's available
	if it.done {
		select {
		case log := <-it.logs:
			it.Event = new(Mit-raExchangeHitTransacted)
			if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
				it.fail = err
				return false
			}
			it.Event.Raw = log
			return true

		default:
			return false
		}
	}
	// Iterator still in progress, wait for either a data or an error event
	select {
	case log := <-it.logs:
		it.Event = new(Mit-raExchangeHitTransacted)
		if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
			it.fail = err
			return false
		}
		it.Event.Raw = log
		return true

	case err := <-it.sub.Err():
		it.done = true
		it.fail = err
		return it.Next()
	}
}

// Error returns any retrieval or parsing error occurred during filtering.
func (it *Mit-raExchangeHitTransactedIterator) Error() error {
	return it.fail
}

// Close terminates the iteration process, releasing any pending underlying
// resources.
func (it *Mit-raExchangeHitTransactedIterator) Close() error {
	it.sub.Unsubscribe()
	return nil
}

// Mit-raExchangeHitTransacted represents a HitTransacted event raised by the Mit-raExchange contract.
type Mit-raExchangeHitTransacted struct {
	Id     [16]byte
	Amount *big.Int
	Raw    types.Log // Blockchain specific contextual infos
}

// FilterHitTransacted is a free log retrieval operation binding the contract event 0x0beb153826af0cb18373da3640116642aefbb4b6fcf160cba453086102ccea1b.
//
// Solidity: event HitTransacted(id indexed bytes16, amount uint256)
func (_Mit-raExchange *Mit-raExchangeFilterer) FilterHitTransacted(opts *bind.FilterOpts, id [][16]byte) (*Mit-raExchangeHitTransactedIterator, error) {

	var idRule []interface{}
	for _, idItem := range id {
		idRule = append(idRule, idItem)
	}

	logs, sub, err := _Mit-raExchange.contract.FilterLogs(opts, "HitTransacted", idRule)
	if err != nil {
		return nil, err
	}
	return &Mit-raExchangeHitTransactedIterator{contract: _Mit-raExchange.contract, event: "HitTransacted", logs: logs, sub: sub}, nil
}

// WatchHitTransacted is a free log subscription operation binding the contract event 0x0beb153826af0cb18373da3640116642aefbb4b6fcf160cba453086102ccea1b.
//
// Solidity: event HitTransacted(id indexed bytes16, amount uint256)
func (_Mit-raExchange *Mit-raExchangeFilterer) WatchHitTransacted(opts *bind.WatchOpts, sink chan<- *Mit-raExchangeHitTransacted, id [][16]byte) (event.Subscription, error) {

	var idRule []interface{}
	for _, idItem := range id {
		idRule = append(idRule, idItem)
	}

	logs, sub, err := _Mit-raExchange.contract.WatchLogs(opts, "HitTransacted", idRule)
	if err != nil {
		return nil, err
	}
	return event.NewSubscription(func(quit <-chan struct{}) error {
		defer sub.Unsubscribe()
		for {
			select {
			case log := <-logs:
				// New log arrived, parse the event and forward to the user
				event := new(Mit-raExchangeHitTransacted)
				if err := _Mit-raExchange.contract.UnpackLog(event, "HitTransacted", log); err != nil {
					return err
				}
				event.Raw = log

				select {
				case sink <- event:
				case err := <-sub.Err():
					return err
				case <-quit:
					return nil
				}
			case err := <-sub.Err():
				return err
			case <-quit:
				return nil
			}
		}
	}), nil
}

// Mit-raExchangeOfferCreatedIterator is returned from FilterOfferCreated and is used to iterate over the raw logs and unpacked data for OfferCreated events raised by the Mit-raExchange contract.
type Mit-raExchangeOfferCreatedIterator struct {
	Event *Mit-raExchangeOfferCreated // Event containing the contract specifics and raw log

	contract *bind.BoundContract // Generic contract to use for unpacking event data
	event    string              // Event name to use for unpacking event data

	logs chan types.Log        // Log channel receiving the found contract events
	sub  ethereum.Subscription // Subscription for errors, completion and termination
	done bool                  // Whether the subscription completed delivering logs
	fail error                 // Occurred error to stop iteration
}

// Next advances the iterator to the subsequent event, returning whether there
// are any more events found. In case of a retrieval or parsing error, false is
// returned and Error() can be queried for the exact failure.
func (it *Mit-raExchangeOfferCreatedIterator) Next() bool {
	// If the iterator failed, stop iterating
	if it.fail != nil {
		return false
	}
	// If the iterator completed, deliver directly whatever's available
	if it.done {
		select {
		case log := <-it.logs:
			it.Event = new(Mit-raExchangeOfferCreated)
			if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
				it.fail = err
				return false
			}
			it.Event.Raw = log
			return true

		default:
			return false
		}
	}
	// Iterator still in progress, wait for either a data or an error event
	select {
	case log := <-it.logs:
		it.Event = new(Mit-raExchangeOfferCreated)
		if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
			it.fail = err
			return false
		}
		it.Event.Raw = log
		return true

	case err := <-it.sub.Err():
		it.done = true
		it.fail = err
		return it.Next()
	}
}

// Error returns any retrieval or parsing error occurred during filtering.
func (it *Mit-raExchangeOfferCreatedIterator) Error() error {
	return it.fail
}

// Close terminates the iteration process, releasing any pending underlying
// resources.
func (it *Mit-raExchangeOfferCreatedIterator) Close() error {
	it.sub.Unsubscribe()
	return nil
}

// Mit-raExchangeOfferCreated represents a OfferCreated event raised by the Mit-raExchange contract.
type Mit-raExchangeOfferCreated struct {
	Id    [16]byte
	Owner [16]byte
	Raw   types.Log // Blockchain specific contextual infos
}

// FilterOfferCreated is a free log retrieval operation binding the contract event 0x3452c2f4f5fd20f28b87971b0ef62e650904e6706f96823bd746ec1050abd679.
//
// Solidity: event OfferCreated(id indexed bytes16, owner indexed bytes16)
func (_Mit-raExchange *Mit-raExchangeFilterer) FilterOfferCreated(opts *bind.FilterOpts, id [][16]byte, owner [][16]byte) (*Mit-raExchangeOfferCreatedIterator, error) {

	var idRule []interface{}
	for _, idItem := range id {
		idRule = append(idRule, idItem)
	}
	var ownerRule []interface{}
	for _, ownerItem := range owner {
		ownerRule = append(ownerRule, ownerItem)
	}

	logs, sub, err := _Mit-raExchange.contract.FilterLogs(opts, "OfferCreated", idRule, ownerRule)
	if err != nil {
		return nil, err
	}
	return &Mit-raExchangeOfferCreatedIterator{contract: _Mit-raExchange.contract, event: "OfferCreated", logs: logs, sub: sub}, nil
}

// WatchOfferCreated is a free log subscription operation binding the contract event 0x3452c2f4f5fd20f28b87971b0ef62e650904e6706f96823bd746ec1050abd679.
//
// Solidity: event OfferCreated(id indexed bytes16, owner indexed bytes16)
func (_Mit-raExchange *Mit-raExchangeFilterer) WatchOfferCreated(opts *bind.WatchOpts, sink chan<- *Mit-raExchangeOfferCreated, id [][16]byte, owner [][16]byte) (event.Subscription, error) {

	var idRule []interface{}
	for _, idItem := range id {
		idRule = append(idRule, idItem)
	}
	var ownerRule []interface{}
	for _, ownerItem := range owner {
		ownerRule = append(ownerRule, ownerItem)
	}

	logs, sub, err := _Mit-raExchange.contract.WatchLogs(opts, "OfferCreated", idRule, ownerRule)
	if err != nil {
		return nil, err
	}
	return event.NewSubscription(func(quit <-chan struct{}) error {
		defer sub.Unsubscribe()
		for {
			select {
			case log := <-logs:
				// New log arrived, parse the event and forward to the user
				event := new(Mit-raExchangeOfferCreated)
				if err := _Mit-raExchange.contract.UnpackLog(event, "OfferCreated", log); err != nil {
					return err
				}
				event.Raw = log

				select {
				case sink <- event:
				case err := <-sub.Err():
					return err
				case <-quit:
					return nil
				}
			case err := <-sub.Err():
				return err
			case <-quit:
				return nil
			}
		}
	}), nil
}

// Mit-raExchangePublisherCreatedIterator is returned from FilterPublisherCreated and is used to iterate over the raw logs and unpacked data for PublisherCreated events raised by the Mit-raExchange contract.
type Mit-raExchangePublisherCreatedIterator struct {
	Event *Mit-raExchangePublisherCreated // Event containing the contract specifics and raw log

	contract *bind.BoundContract // Generic contract to use for unpacking event data
	event    string              // Event name to use for unpacking event data

	logs chan types.Log        // Log channel receiving the found contract events
	sub  ethereum.Subscription // Subscription for errors, completion and termination
	done bool                  // Whether the subscription completed delivering logs
	fail error                 // Occurred error to stop iteration
}

// Next advances the iterator to the subsequent event, returning whether there
// are any more events found. In case of a retrieval or parsing error, false is
// returned and Error() can be queried for the exact failure.
func (it *Mit-raExchangePublisherCreatedIterator) Next() bool {
	// If the iterator failed, stop iterating
	if it.fail != nil {
		return false
	}
	// If the iterator completed, deliver directly whatever's available
	if it.done {
		select {
		case log := <-it.logs:
			it.Event = new(Mit-raExchangePublisherCreated)
			if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
				it.fail = err
				return false
			}
			it.Event.Raw = log
			return true

		default:
			return false
		}
	}
	// Iterator still in progress, wait for either a data or an error event
	select {
	case log := <-it.logs:
		it.Event = new(Mit-raExchangePublisherCreated)
		if err := it.contract.UnpackLog(it.Event, it.event, log); err != nil {
			it.fail = err
			return false
		}
		it.Event.Raw = log
		return true

	case err := <-it.sub.Err():
		it.done = true
		it.fail = err
		return it.Next()
	}
}

// Error returns any retrieval or parsing error occurred during filtering.
func (it *Mit-raExchangePublisherCreatedIterator) Error() error {
	return it.fail
}

// Close terminates the iteration process, releasing any pending underlying
// resources.
func (it *Mit-raExchangePublisherCreatedIterator) Close() error {
	it.sub.Unsubscribe()
	return nil
}

// Mit-raExchangePublisherCreated represents a PublisherCreated event raised by the Mit-raExchange contract.
type Mit-raExchangePublisherCreated struct {
	Id    [16]byte
	Owner common.Address
	Raw   types.Log // Blockchain specific contextual infos
}

// FilterPublisherCreated is a free log retrieval operation binding the contract event 0x64f6c400b090ba2031d25a03826d652b5d62a7c18b5f523b38852a9c30b69103.
//
// Solidity: event PublisherCreated(id indexed bytes16, owner indexed address)
func (_Mit-raExchange *Mit-raExchangeFilterer) FilterPublisherCreated(opts *bind.FilterOpts, id [][16]byte, owner []common.Address) (*Mit-raExchangePublisherCreatedIterator, error) {

	var idRule []interface{}
	for _, idItem := range id {
		idRule = append(idRule, idItem)
	}
	var ownerRule []interface{}
	for _, ownerItem := range owner {
		ownerRule = append(ownerRule, ownerItem)
	}

	logs, sub, err := _Mit-raExchange.contract.FilterLogs(opts, "PublisherCreated", idRule, ownerRule)
	if err != nil {
		return nil, err
	}
	return &Mit-raExchangePublisherCreatedIterator{contract: _Mit-raExchange.contract, event: "PublisherCreated", logs: logs, sub: sub}, nil
}

// WatchPublisherCreated is a free log subscription operation binding the contract event 0x64f6c400b090ba2031d25a03826d652b5d62a7c18b5f523b38852a9c30b69103.
//
// Solidity: event PublisherCreated(id indexed bytes16, owner indexed address)
func (_Mit-raExchange *Mit-raExchangeFilterer) WatchPublisherCreated(opts *bind.WatchOpts, sink chan<- *Mit-raExchangePublisherCreated, id [][16]byte, owner []common.Address) (event.Subscription, error) {

	var idRule []interface{}
	for _, idItem := range id {
		idRule = append(idRule, idItem)
	}
	var ownerRule []interface{}
	for _, ownerItem := range owner {
		ownerRule = append(ownerRule, ownerItem)
	}

	logs, sub, err := _Mit-raExchange.contract.WatchLogs(opts, "PublisherCreated", idRule, ownerRule)
	if err != nil {
		return nil, err
	}
	return event.NewSubscription(func(quit <-chan struct{}) error {
		defer sub.Unsubscribe()
		for {
			select {
			case log := <-logs:
				// New log arrived, parse the event and forward to the user
				event := new(Mit-raExchangePublisherCreated)
				if err := _Mit-raExchange.contract.UnpackLog(event, "PublisherCreated", log); err != nil {
					return err
				}
				event.Raw = log

				select {
				case sink <- event:
				case err := <-sub.Err():
					return err
				case <-quit:
					return nil
				}
			case err := <-sub.Err():
				return err
			case <-quit:
				return nil
			}
		}
	}), nil
}

// Mit-raStorageABI is the input ABI used to generate the binding from.
const Mit-raStorageABI = "[{\"constant\":true,\"inputs\":[],\"name\":\"systemOwner\",\"outputs\":[{\"name\":\"\",\"type\":\"address\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"owner\",\"type\":\"address\"},{\"name\":\"role\",\"type\":\"uint8\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"rank\",\"type\":\"uint8\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"setUser\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"systemOwnerAddress\",\"type\":\"address\"}],\"name\":\"setSystemOwner\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[{\"name\":\"\",\"type\":\"bytes16\"}],\"name\":\"users\",\"outputs\":[{\"name\":\"created\",\"type\":\"uint256\"},{\"name\":\"owner\",\"type\":\"address\"},{\"name\":\"role\",\"type\":\"uint8\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"rank\",\"type\":\"uint8\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"owner\",\"type\":\"bytes16\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"url\",\"type\":\"string\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"categories\",\"type\":\"uint16[]\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"setAdSpace\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[{\"name\":\"\",\"type\":\"bytes16\"}],\"name\":\"adSpaces\",\"outputs\":[{\"name\":\"created\",\"type\":\"uint256\"},{\"name\":\"owner\",\"type\":\"bytes16\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"url\",\"type\":\"string\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[{\"name\":\"\",\"type\":\"bytes16\"}],\"name\":\"hits\",\"outputs\":[{\"name\":\"created\",\"type\":\"uint256\"},{\"name\":\"hitType\",\"type\":\"uint8\"},{\"name\":\"session\",\"type\":\"bytes16\"},{\"name\":\"space\",\"type\":\"bytes16\"},{\"name\":\"offer\",\"type\":\"bytes16\"},{\"name\":\"amount\",\"type\":\"uint256\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":true,\"inputs\":[{\"name\":\"\",\"type\":\"bytes16\"}],\"name\":\"offers\",\"outputs\":[{\"name\":\"created\",\"type\":\"uint256\"},{\"name\":\"owner\",\"type\":\"bytes16\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"hitPrice\",\"type\":\"uint256\"},{\"name\":\"actionPrice\",\"type\":\"uint256\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"payable\":false,\"stateMutability\":\"view\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"owner\",\"type\":\"bytes16\"},{\"name\":\"name\",\"type\":\"string\"},{\"name\":\"hitPrice\",\"type\":\"uint256\"},{\"name\":\"actionPrice\",\"type\":\"uint256\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"categories\",\"type\":\"uint16[]\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"setOffer\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"constant\":false,\"inputs\":[{\"name\":\"id\",\"type\":\"bytes16\"},{\"name\":\"hitType\",\"type\":\"uint8\"},{\"name\":\"session\",\"type\":\"bytes16\"},{\"name\":\"space\",\"type\":\"bytes16\"},{\"name\":\"offer\",\"type\":\"bytes16\"},{\"name\":\"amount\",\"type\":\"uint256\"},{\"name\":\"details\",\"type\":\"string\"},{\"name\":\"categories\",\"type\":\"uint16[]\"},{\"name\":\"state\",\"type\":\"uint8\"}],\"name\":\"setHit\",\"outputs\":[],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"function\"},{\"inputs\":[{\"name\":\"systemOwnerAddress\",\"type\":\"address\"}],\"payable\":false,\"stateMutability\":\"nonpayable\",\"type\":\"constructor\"}]"

// Mit-raStorageBin is the compiled bytecode used for deploying new contracts.
const Mit-raStorageBin = `0x608060405234801561001057600080fd5b506040516020806128c5833981016040525160048054600160a060020a031916600160a060020a03909216919091179055612875806100506000396000f3006080604052600436106100a35763ffffffff7c01000000000000000000000000000000000000000000000000000000006000350416633377925481146100a85780634034aad9146100d9578063621eb9a2146101a55780637520dd14146101c65780637e4a3d4f1461031c57806384f1f966146104465780639ee3ad4414610596578063c32d869b1461064a578063f26b7f9b14610744578063ff2e6ec41461083d575b600080fd5b3480156100b457600080fd5b506100bd610902565b60408051600160a060020a039092168252519081900360200190f35b3480156100e557600080fd5b50604080516020601f6064356004818101359283018490048402850184019095528184526101a3946001608060020a031981351694600160a060020a0360248035919091169560ff60443516953695608494930191819084018382808284375050604080516020601f89358b018035918201839004830284018301909452808352979a9998810197919650918201945092508291508401838280828437509497505060ff853581169650602090950135909416935061091192505050565b005b3480156101b157600080fd5b506101a3600160a060020a0360043516610f35565b3480156101d257600080fd5b506101e86001608060020a031960043516610ff1565b60408051888152600160a060020a038816602082015290810186600281111561020d57fe5b60ff168152602001806020018060200185600681111561022957fe5b60ff16815260200184600581111561023d57fe5b60ff168152602001838103835287818151815260200191508051906020019080838360005b8381101561027a578181015183820152602001610262565b50505050905090810190601f1680156102a75780820380516001836020036101000a031916815260200191505b50838103825286518152865160209182019188019080838360005b838110156102da5781810151838201526020016102c2565b50505050905090810190601f1680156103075780820380516001836020036101000a031916815260200191505b50995050505050505050505060405180910390f35b34801561032857600080fd5b50604080516020600460443581810135601f81018490048402850184019095528484526101a39482356001608060020a03199081169560248035909216953695946064949293019190819084018382808284375050604080516020601f89358b018035918201839004830284018301909452808352979a99988101979196509182019450925082915084018382808284375050604080516020601f89358b018035918201839004830284018301909452808352979a999881019791965091820194509250829150840183828082843750506040805187358901803560208181028481018201909552818452989b9a9989019892975090820195509350839250850190849080828437509497505050923560ff16935061116392505050565b34801561045257600080fd5b506104686001608060020a03196004351661174c565b604080518781526001608060020a031987166020820152908101606082016080830160a0840185600581111561049a57fe5b60ff168152602001848103845288818151815260200191508051906020019080838360005b838110156104d75781810151838201526020016104bf565b50505050905090810190601f1680156105045780820380516001836020036101000a031916815260200191505b50848103835287518152875160209182019189019080838360005b8381101561053757818101518382015260200161051f565b50505050905090810190601f1680156105645780820380516001836020036101000a031916815260200191505b5084810382528651815286516020918201918801908083836000838110156102da5781810151838201526020016102c2565b3480156105a257600080fd5b506105b86001608060020a031960043516611925565b604051808981526020018860028111156105ce57fe5b60ff1681526001608060020a031980891660208301528781166040830152861660608201526080810185905260a081019060c00183600581111561060e57fe5b60ff16815260200182810382528481815181526020019150805190602001908083836000838110156102da5781810151838201526020016102c2565b34801561065657600080fd5b5061066c6001608060020a031960043516611a00565b604080518881526001608060020a031988166020820152606081018690526080810185905290810160a0820160c083018460058111156106a857fe5b60ff168152602001838103835288818151815260200191508051906020019080838360005b838110156106e55781810151838201526020016106cd565b50505050905090810190601f1680156107125780820380516001836020036101000a031916815260200191505b5083810382528551815285516020918201918701908083836000838110156102da5781810151838201526020016102c2565b34801561075057600080fd5b50604080516020600460443581810135601f81018490048402850184019095528484526101a39482356001608060020a03199081169560248035909216953695946064949293019190819084018382808284375050604080516020888301358a018035601f8101839004830284018301909452838352979a89359a8a8301359a91999098506060909101965091945090810192508190840183828082843750506040805187358901803560208181028481018201909552818452989b9a9989019892975090820195509350839250850190849080828437509497505050923560ff169350611b6692505050565b34801561084957600080fd5b50604080516020600460c43581810135601f81018490048402850184019095528484526101a39482356001608060020a0319908116956024803560ff16966044358416966064358516966084359095169560a435953695929460e494910191908190840183828082843750506040805187358901803560208181028481018201909552818452989b9a9989019892975090820195509350839250850190849080828437509497505050923560ff16935061210592505050565b600454600160a060020a031681565b600480546040805160e160020a6317aa5fb7028152600160a060020a033381169482019490945290519290911691632f54bf6e916024808201926020929091908290030181600087803b15801561096757600080fd5b505af115801561097b573d6000803e3d6000fd5b505050506040513d602081101561099157600080fd5b5051151561099e57600080fd5b60006001608060020a03198816600090815260208190526040902060040154610100900460ff1660058111156109d057fe5b1415610b505760e06040519081016040528042815260200187600160a060020a03168152602001866002811115610a0357fe5b8152602001858152602001848152602001836006811115610a2057fe5b8152602001826005811115610a3157fe5b90526001608060020a0319881660009081526020818152604091829020835181559083015160018201805473ffffffffffffffffffffffffffffffffffffffff1916600160a060020a039092169190911780825592840151919274ff0000000000000000000000000000000000000000191674010000000000000000000000000000000000000000836002811115610ac557fe5b021790555060608201518051610ae59160028401916020909101906126ea565b5060808201518051610b019160038401916020909101906126ea565b5060a082015160048201805460ff19166001836006811115610b1f57fe5b021790555060c082015160048201805461ff001916610100836005811115610b4357fe5b0217905550905050610f2c565b6040805160e0810182526001608060020a0319891660009081526020818152929020548152908101600160a060020a03881615610b8d5787610bb4565b6001608060020a03198916600090815260208190526040902060010154600160a060020a03165b600160a060020a031681526001608060020a031989166000908152602081815260409091206001015491019074010000000000000000000000000000000000000000900460ff166002811115610c0657fe5b81526020018551600014610c1a5785610cc0565b6001608060020a03198916600090815260208181526040918290206002908101805484516001821615610100026000190190911692909204601f810184900484028301840190945283825290929091830182828015610cba5780601f10610c8f57610100808354040283529160200191610cba565b820191906000526020600020905b815481529060010190602001808311610c9d57829003601f168201915b50505050505b81526020018451600014610cd45784610d79565b6001608060020a031989166000908152602081815260409182902060030180548351601f600260001961010060018616150201909316929092049182018490048402810184019094528084529091830182828015610d735780601f10610d4857610100808354040283529160200191610d73565b820191906000526020600020905b815481529060010190602001808311610d5657829003601f168201915b50505050505b81526020016000846006811115610d8c57fe5b14610d975783610db8565b6001608060020a0319891660009081526020819052604090206004015460ff165b6006811115610dc357fe5b81526020016000836005811115610dd657fe5b14610de15782610e07565b6001608060020a03198916600090815260208190526040902060040154610100900460ff165b6005811115610e1257fe5b90526001608060020a0319881660009081526020818152604091829020835181559083015160018201805473ffffffffffffffffffffffffffffffffffffffff1916600160a060020a039092169190911780825592840151919274ff0000000000000000000000000000000000000000191674010000000000000000000000000000000000000000836002811115610ea657fe5b021790555060608201518051610ec69160028401916020909101906126ea565b5060808201518051610ee29160038401916020909101906126ea565b5060a082015160048201805460ff19166001836006811115610f0057fe5b021790555060c082015160048201805461ff001916610100836005811115610f2457fe5b021790555050505b50505050505050565b600480546040805160e160020a6317aa5fb7028152600160a060020a033381169482019490945290519290911691632f54bf6e916024808201926020929091908290030181600087803b158015610f8b57600080fd5b505af1158015610f9f573d6000803e3d6000fd5b505050506040513d6020811015610fb557600080fd5b50511515610fc257600080fd5b6004805473ffffffffffffffffffffffffffffffffffffffff1916600160a060020a0392909216919091179055565b6000602081815291815260409081902080546001808301546002808501805487516101009582161595909502600019011691909104601f81018890048802840188019096528583529295600160a060020a038216957401000000000000000000000000000000000000000090920460ff16949391908301828280156110b75780601f1061108c576101008083540402835291602001916110b7565b820191906000526020600020905b81548152906001019060200180831161109a57829003601f168201915b5050505060038301805460408051602060026001851615610100026000190190941693909304601f81018490048402820184019092528181529495949350908301828280156111475780601f1061111c57610100808354040283529160200191611147565b820191906000526020600020905b81548152906001019060200180831161112a57829003601f168201915b5050506004909301549192505060ff8082169161010090041687565b600480546040805160e160020a6317aa5fb7028152600160a060020a033381169482019490945290519290911691632f54bf6e916024808201926020929091908290030181600087803b1580156111b957600080fd5b505af11580156111cd573d6000803e3d6000fd5b505050506040513d60208110156111e357600080fd5b505115156111f057600080fd5b6001608060020a0319871660009081526001602052604081206006015460ff16600581111561121b57fe5b14156113325760e060405190810160405280428152602001876001608060020a031916815260200186815260200185815260200184815260200183815260200182600581111561126757fe5b90526001608060020a031988811660009081526001602081815260409283902085518155858201519281018054909516608060020a9093049290921790935590830151805191926112c0926002850192909101906126ea565b50606082015180516112dc9160038401916020909101906126ea565b50608082015180516112f89160048401916020909101906126ea565b5060a08201518051611314916005840191602090910190612768565b5060c082015160068201805460ff19166001836005811115610b4357fe5b6040805160e0810182526001608060020a03198916600090815260016020908152929020548152908101876001608060020a0319168152602001865160001461137b578661141f565b6001608060020a031989166000908152600160208181526040928390206002908101805485519481161561010002600019011691909104601f81018390048302840183019094528383529192908301828280156114195780601f106113ee57610100808354040283529160200191611419565b820191906000526020600020905b8154815290600101906020018083116113fc57829003601f168201915b50505050505b8152602001855160001461143357856114d9565b6001608060020a0319891660009081526001602081815260409283902060030180548451600294821615610100026000190190911693909304601f81018390048302840183019094528383529192908301828280156114d35780601f106114a8576101008083540402835291602001916114d3565b820191906000526020600020905b8154815290600101906020018083116114b657829003601f168201915b50505050505b815260200184516000146114ed5784611593565b6001608060020a0319891660009081526001602081815260409283902060040180548451600294821615610100026000190190911693909304601f810183900483028401830190945283835291929083018282801561158d5780601f106115625761010080835404028352916020019161158d565b820191906000526020600020905b81548152906001019060200180831161157057829003601f168201915b50505050505b815260200183516000146115a75783611637565b6001608060020a031989166000908152600160209081526040918290206005018054835181840281018401909452808452909183018282801561163157602002820191906000526020600020906000905b82829054906101000a900461ffff1661ffff16815260200190600201906020826001010492830192600103820291508084116115f85790505b50505050505b8152602001600083600581111561164a57fe5b146116555782611676565b6001608060020a0319891660009081526001602052604090206006015460ff165b600581111561168157fe5b90526001608060020a031988811660009081526001602081815260409283902085518155858201519281018054909516608060020a9093049290921790935590830151805191926116da926002850192909101906126ea565b50606082015180516116f69160038401916020909101906126ea565b50608082015180516117129160048401916020909101906126ea565b5060a0820151805161172e916005840191602090910190612768565b5060c082015160068201805460ff19166001836005811115610f2457fe5b6001602081815260009283526040928390208054818401546002808401805488516101009882161598909802600019011691909104601f81018690048602870186019097528686529195608060020a9091029492938301828280156117f25780601f106117c7576101008083540402835291602001916117f2565b820191906000526020600020905b8154815290600101906020018083116117d557829003601f168201915b5050505060038301805460408051602060026001851615610100026000190190941693909304601f81018490048402820184019092528181529495949350908301828280156118825780601f1061185757610100808354040283529160200191611882565b820191906000526020600020905b81548152906001019060200180831161186557829003601f168201915b5050505060048301805460408051602060026001851615610100026000190190941693909304601f81018490048402820184019092528181529495949350908301828280156119125780601f106118e757610100808354040283529160200191611912565b820191906000526020600020905b8154815290600101906020018083116118f557829003601f168201915b5050506006909301549192505060ff1686565b6003602081815260009283526040928390208054600180830154600280850154968501546004860180548a516101009682161587026000190190911693909304601f8101899004890284018901909a52898352949860ff84169894909304608060020a90810297818602979582900490910295919493908301828280156119ed5780601f106119c2576101008083540402835291602001916119ed565b820191906000526020600020905b8154815290600101906020018083116119d057829003601f168201915b5050506006909301549192505060ff1688565b600260208181526000928352604092839020805460018083015483860180548851601f600019958316156101000295909501909116979097049283018690048602870186019097528186529195608060020a909202949293830182828015611aa95780601f10611a7e57610100808354040283529160200191611aa9565b820191906000526020600020905b815481529060010190602001808311611a8c57829003601f168201915b505050505090806003015490806004015490806005018054600181600116156101000203166002900480601f016020809104026020016040519081016040528092919081815260200182805460018160011615610100020316600290048015611b535780601f10611b2857610100808354040283529160200191611b53565b820191906000526020600020905b815481529060010190602001808311611b3657829003601f168201915b5050506007909301549192505060ff1687565b600480546040805160e160020a6317aa5fb7028152600160a060020a033381169482019490945290519290911691632f54bf6e916024808201926020929091908290030181600087803b158015611bbc57600080fd5b505af1158015611bd0573d6000803e3d6000fd5b505050506040513d6020811015611be657600080fd5b50511515611bf357600080fd5b6001608060020a0319881660009081526002602052604081206007015460ff166005811115611c1e57fe5b1415611d3d5761010060405190810160405280428152602001886001608060020a0319168152602001878152602001868152602001858152602001848152602001838152602001826005811115611c7157fe5b90526001608060020a03198981166000908152600260208181526040928390208551815585820151600182018054909616608060020a90910417909455918401518051611cc6939285019291909101906126ea565b50606082015160038201556080820151600482015560a08201518051611cf69160058401916020909101906126ea565b5060c08201518051611d12916006840191602090910190612768565b5060e082015160078201805460ff19166001836005811115611d3057fe5b02179055509050506120fb565b60408051610100810182526001608060020a03198a16600090815260026020908152929020548152908101886001608060020a03191681526020018751600014611d875787611e2b565b6001608060020a03198a166000908152600260208181526040928390208201805484516001821615610100026000190190911693909304601f8101839004830284018301909452838352919290830182828015611e255780601f10611dfa57610100808354040283529160200191611e25565b820191906000526020600020905b815481529060010190602001808311611e0857829003601f168201915b50505050505b815260200160008710611e3e5786611e5c565b6001608060020a03198a166000908152600260205260409020600301545b815260200160008610611e6f5785611e8d565b6001608060020a03198a166000908152600260205260409020600401545b81526020018451600014611ea15784611f46565b6001608060020a03198a16600090815260026020818152604092839020600501805484516001821615610100026000190190911693909304601f8101839004830284018301909452838352919290830182828015611f405780601f10611f1557610100808354040283529160200191611f40565b820191906000526020600020905b815481529060010190602001808311611f2357829003601f168201915b50505050505b81526020018351600014611f5a5783611fea565b6001608060020a03198a1660009081526002602090815260409182902060060180548351818402810184019094528084529091830182828015611fe457602002820191906000526020600020906000905b82829054906101000a900461ffff1661ffff1681526020019060020190602082600101049283019260010382029150808411611fab5790505b50505050505b81526020016000836005811115611ffd57fe5b146120085782612029565b6001608060020a03198a1660009081526002602052604090206007015460ff165b600581111561203457fe5b90526001608060020a03198981166000908152600260208181526040928390208551815585820151600182018054909616608060020a90910417909455918401518051612089939285019291909101906126ea565b50606082015160038201556080820151600482015560a082015180516120b99160058401916020909101906126ea565b5060c082015180516120d5916006840191602090910190612768565b5060e082015160078201805460ff191660018360058111156120f357fe5b021790555050505b5050505050505050565b600480546040805160e160020a6317aa5fb7028152600160a060020a033381169482019490945290519290911691632f54bf6e916024808201926020929091908290030181600087803b15801561215b57600080fd5b505af115801561216f573d6000803e3d6000fd5b505050506040513d602081101561218557600080fd5b5051151561219257600080fd5b6001608060020a0319891660009081526003602052604081206006015460ff1660058111156121bd57fe5b141561234f57610120604051908101604052804281526020018960028111156121e257fe5b8152602001886001608060020a0319168152602001876001608060020a0319168152602001866001608060020a031916815260200185815260200184815260200183815260200182600581111561223557fe5b90526001608060020a03198a166000908152600360209081526040909120825181559082015160018083018054909160ff199091169083600281111561227757fe5b0217905550604082015160018201805470ffffffffffffffffffffffffffffffff001916610100608060020a9384900402179055606083015160028301805460808601516001608060020a036001608060020a03199092169385900493909317169183900490920217905560a0820151600382015560c082015180516123079160048401916020909101906126ea565b5060e08201518051612323916005840191602090910190612768565b5061010082015160068201805460ff1916600183600581111561234257fe5b02179055509050506126df565b60408051610120810182526001608060020a03198b1660009081526003602090815292812054825290918201908a600281111561238857fe5b1461239357896123b4565b6001608060020a03198b1660009081526003602052604090206001015460ff165b60028111156123bf57fe5b8152602001886001608060020a0319168152602001876001608060020a0319168152602001866001608060020a0319168152602001600086106124025785612421565b6001608060020a03198b16600090815260036020819052604090912001545b8152602001845160001461243557846124dc565b6001608060020a03198b1660009081526003602090815260409182902060040180548351601f6002600019610100600186161502019093169290920491820184900484028101840190945280845290918301828280156124d65780601f106124ab576101008083540402835291602001916124d6565b820191906000526020600020905b8154815290600101906020018083116124b957829003601f168201915b50505050505b815260200183516000146124f05783612580565b6001608060020a03198b166000908152600360209081526040918290206005018054835181840281018401909452808452909183018282801561257a57602002820191906000526020600020906000905b82829054906101000a900461ffff1661ffff16815260200190600201906020826001010492830192600103820291508084116125415790505b50505050505b8152602001600083600581111561259357fe5b1461259e57826125bf565b6001608060020a03198b1660009081526003602052604090206006015460ff165b60058111156125ca57fe5b90526001608060020a03198a166000908152600360209081526040909120825181559082015160018083018054909160ff199091169083600281111561260c57fe5b0217905550604082015160018201805470ffffffffffffffffffffffffffffffff001916610100608060020a9384900402179055606083015160028301805460808601516001608060020a036001608060020a03199092169385900493909317169183900490920217905560a0820151600382015560c0820151805161269c9160048401916020909101906126ea565b5060e082015180516126b8916005840191602090910190612768565b5061010082015160068201805460ff191660018360058111156126d757fe5b021790555050505b505050505050505050565b828054600181600116156101000203166002900490600052602060002090601f016020900481019282601f1061272b57805160ff1916838001178555612758565b82800160010185558215612758579182015b8281111561275857825182559160200191906001019061273d565b5061276492915061280d565b5090565b82805482825590600052602060002090600f016010900481019282156128015791602002820160005b838211156127d157835183826101000a81548161ffff021916908361ffff1602179055509260200192600201602081600101049283019260010302612791565b80156127ff5782816101000a81549061ffff02191690556002016020816001010492830192600103026127d1565b505b5061276492915061282a565b61282791905b808211156127645760008155600101612813565b90565b61282791905b8082111561276457805461ffff191681556001016128305600a165627a7a72305820d59f96c711fd6fc5e3577191160231dab5e9856d127a39e3824afcf3088d66620029`

// DeployMit-raStorage deploys a new Ethereum contract, binding an instance of Mit-raStorage to it.
func DeployMit-raStorage(auth *bind.TransactOpts, backend bind.ContractBackend, systemOwnerAddress common.Address) (common.Address, *types.Transaction, *Mit-raStorage, error) {
	parsed, err := abi.JSON(strings.NewReader(Mit-raStorageABI))
	if err != nil {
		return common.Address{}, nil, nil, err
	}
	address, tx, contract, err := bind.DeployContract(auth, parsed, common.FromHex(Mit-raStorageBin), backend, systemOwnerAddress)
	if err != nil {
		return common.Address{}, nil, nil, err
	}
	return address, tx, &Mit-raStorage{Mit-raStorageCaller: Mit-raStorageCaller{contract: contract}, Mit-raStorageTransactor: Mit-raStorageTransactor{contract: contract}, Mit-raStorageFilterer: Mit-raStorageFilterer{contract: contract}}, nil
}

// Mit-raStorage is an auto generated Go binding around an Ethereum contract.
type Mit-raStorage struct {
	Mit-raStorageCaller     // Read-only binding to the contract
	Mit-raStorageTransactor // Write-only binding to the contract
	Mit-raStorageFilterer   // Log filterer for contract events
}

// Mit-raStorageCaller is an auto generated read-only Go binding around an Ethereum contract.
type Mit-raStorageCaller struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// Mit-raStorageTransactor is an auto generated write-only Go binding around an Ethereum contract.
type Mit-raStorageTransactor struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// Mit-raStorageFilterer is an auto generated log filtering Go binding around an Ethereum contract events.
type Mit-raStorageFilterer struct {
	contract *bind.BoundContract // Generic contract wrapper for the low level calls
}

// Mit-raStorageSession is an auto generated Go binding around an Ethereum contract,
// with pre-set call and transact options.
type Mit-raStorageSession struct {
	Contract     *Mit-raStorage      // Generic contract binding to set the session for
	CallOpts     bind.CallOpts     // Call options to use throughout this session
	TransactOpts bind.TransactOpts // Transaction auth options to use throughout this session
}

// Mit-raStorageCallerSession is an auto generated read-only Go binding around an Ethereum contract,
// with pre-set call options.
type Mit-raStorageCallerSession struct {
	Contract *Mit-raStorageCaller // Generic contract caller binding to set the session for
	CallOpts bind.CallOpts      // Call options to use throughout this session
}

// Mit-raStorageTransactorSession is an auto generated write-only Go binding around an Ethereum contract,
// with pre-set transact options.
type Mit-raStorageTransactorSession struct {
	Contract     *Mit-raStorageTransactor // Generic contract transactor binding to set the session for
	TransactOpts bind.TransactOpts      // Transaction auth options to use throughout this session
}

// Mit-raStorageRaw is an auto generated low-level Go binding around an Ethereum contract.
type Mit-raStorageRaw struct {
	Contract *Mit-raStorage // Generic contract binding to access the raw methods on
}

// Mit-raStorageCallerRaw is an auto generated low-level read-only Go binding around an Ethereum contract.
type Mit-raStorageCallerRaw struct {
	Contract *Mit-raStorageCaller // Generic read-only contract binding to access the raw methods on
}

// Mit-raStorageTransactorRaw is an auto generated low-level write-only Go binding around an Ethereum contract.
type Mit-raStorageTransactorRaw struct {
	Contract *Mit-raStorageTransactor // Generic write-only contract binding to access the raw methods on
}

// NewMit-raStorage creates a new instance of Mit-raStorage, bound to a specific deployed contract.
func NewMit-raStorage(address common.Address, backend bind.ContractBackend) (*Mit-raStorage, error) {
	contract, err := bindMit-raStorage(address, backend, backend, backend)
	if err != nil {
		return nil, err
	}
	return &Mit-raStorage{Mit-raStorageCaller: Mit-raStorageCaller{contract: contract}, Mit-raStorageTransactor: Mit-raStorageTransactor{contract: contract}, Mit-raStorageFilterer: Mit-raStorageFilterer{contract: contract}}, nil
}

// NewMit-raStorageCaller creates a new read-only instance of Mit-raStorage, bound to a specific deployed contract.
func NewMit-raStorageCaller(address common.Address, caller bind.ContractCaller) (*Mit-raStorageCaller, error) {
	contract, err := bindMit-raStorage(address, caller, nil, nil)
	if err != nil {
		return nil, err
	}
	return &Mit-raStorageCaller{contract: contract}, nil
}

// NewMit-raStorageTransactor creates a new write-only instance of Mit-raStorage, bound to a specific deployed contract.
func NewMit-raStorageTransactor(address common.Address, transactor bind.ContractTransactor) (*Mit-raStorageTransactor, error) {
	contract, err := bindMit-raStorage(address, nil, transactor, nil)
	if err != nil {
		return nil, err
	}
	return &Mit-raStorageTransactor{contract: contract}, nil
}

// NewMit-raStorageFilterer creates a new log filterer instance of Mit-raStorage, bound to a specific deployed contract.
func NewMit-raStorageFilterer(address common.Address, filterer bind.ContractFilterer) (*Mit-raStorageFilterer, error) {
	contract, err := bindMit-raStorage(address, nil, nil, filterer)
	if err != nil {
		return nil, err
	}
	return &Mit-raStorageFilterer{contract: contract}, nil
}

// bindMit-raStorage binds a generic wrapper to an already deployed contract.
func bindMit-raStorage(address common.Address, caller bind.ContractCaller, transactor bind.ContractTransactor, filterer bind.ContractFilterer) (*bind.BoundContract, error) {
	parsed, err := abi.JSON(strings.NewReader(Mit-raStorageABI))
	if err != nil {
		return nil, err
	}
	return bind.NewBoundContract(address, parsed, caller, transactor, filterer), nil
}

// Call invokes the (constant) contract method with params as input values and
// sets the output to result. The result type might be a single field for simple
// returns, a slice of interfaces for anonymous returns and a struct for named
// returns.
func (_Mit-raStorage *Mit-raStorageRaw) Call(opts *bind.CallOpts, result interface{}, method string, params ...interface{}) error {
	return _Mit-raStorage.Contract.Mit-raStorageCaller.contract.Call(opts, result, method, params...)
}

// Transfer initiates a plain transaction to move funds to the contract, calling
// its default method if one is available.
func (_Mit-raStorage *Mit-raStorageRaw) Transfer(opts *bind.TransactOpts) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.Mit-raStorageTransactor.contract.Transfer(opts)
}

// Transact invokes the (paid) contract method with params as input values.
func (_Mit-raStorage *Mit-raStorageRaw) Transact(opts *bind.TransactOpts, method string, params ...interface{}) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.Mit-raStorageTransactor.contract.Transact(opts, method, params...)
}

// Call invokes the (constant) contract method with params as input values and
// sets the output to result. The result type might be a single field for simple
// returns, a slice of interfaces for anonymous returns and a struct for named
// returns.
func (_Mit-raStorage *Mit-raStorageCallerRaw) Call(opts *bind.CallOpts, result interface{}, method string, params ...interface{}) error {
	return _Mit-raStorage.Contract.contract.Call(opts, result, method, params...)
}

// Transfer initiates a plain transaction to move funds to the contract, calling
// its default method if one is available.
func (_Mit-raStorage *Mit-raStorageTransactorRaw) Transfer(opts *bind.TransactOpts) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.contract.Transfer(opts)
}

// Transact invokes the (paid) contract method with params as input values.
func (_Mit-raStorage *Mit-raStorageTransactorRaw) Transact(opts *bind.TransactOpts, method string, params ...interface{}) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.contract.Transact(opts, method, params...)
}

// AdSpaces is a free data retrieval call binding the contract method 0x84f1f966.
//
// Solidity: function adSpaces( bytes16) constant returns(created uint256, owner bytes16, name string, url string, details string, state uint8)
func (_Mit-raStorage *Mit-raStorageCaller) AdSpaces(opts *bind.CallOpts, arg0 [16]byte) (struct {
	Created *big.Int
	Owner   [16]byte
	Name    string
	Url     string
	Details string
	State   uint8
}, error) {
	ret := new(struct {
		Created *big.Int
		Owner   [16]byte
		Name    string
		Url     string
		Details string
		State   uint8
	})
	out := ret
	err := _Mit-raStorage.contract.Call(opts, out, "adSpaces", arg0)
	return *ret, err
}

// AdSpaces is a free data retrieval call binding the contract method 0x84f1f966.
//
// Solidity: function adSpaces( bytes16) constant returns(created uint256, owner bytes16, name string, url string, details string, state uint8)
func (_Mit-raStorage *Mit-raStorageSession) AdSpaces(arg0 [16]byte) (struct {
	Created *big.Int
	Owner   [16]byte
	Name    string
	Url     string
	Details string
	State   uint8
}, error) {
	return _Mit-raStorage.Contract.AdSpaces(&_Mit-raStorage.CallOpts, arg0)
}

// AdSpaces is a free data retrieval call binding the contract method 0x84f1f966.
//
// Solidity: function adSpaces( bytes16) constant returns(created uint256, owner bytes16, name string, url string, details string, state uint8)
func (_Mit-raStorage *Mit-raStorageCallerSession) AdSpaces(arg0 [16]byte) (struct {
	Created *big.Int
	Owner   [16]byte
	Name    string
	Url     string
	Details string
	State   uint8
}, error) {
	return _Mit-raStorage.Contract.AdSpaces(&_Mit-raStorage.CallOpts, arg0)
}

// Hits is a free data retrieval call binding the contract method 0x9ee3ad44.
//
// Solidity: function hits( bytes16) constant returns(created uint256, hitType uint8, session bytes16, space bytes16, offer bytes16, amount uint256, details string, state uint8)
func (_Mit-raStorage *Mit-raStorageCaller) Hits(opts *bind.CallOpts, arg0 [16]byte) (struct {
	Created *big.Int
	HitType uint8
	Session [16]byte
	Space   [16]byte
	Offer   [16]byte
	Amount  *big.Int
	Details string
	State   uint8
}, error) {
	ret := new(struct {
		Created *big.Int
		HitType uint8
		Session [16]byte
		Space   [16]byte
		Offer   [16]byte
		Amount  *big.Int
		Details string
		State   uint8
	})
	out := ret
	err := _Mit-raStorage.contract.Call(opts, out, "hits", arg0)
	return *ret, err
}

// Hits is a free data retrieval call binding the contract method 0x9ee3ad44.
//
// Solidity: function hits( bytes16) constant returns(created uint256, hitType uint8, session bytes16, space bytes16, offer bytes16, amount uint256, details string, state uint8)
func (_Mit-raStorage *Mit-raStorageSession) Hits(arg0 [16]byte) (struct {
	Created *big.Int
	HitType uint8
	Session [16]byte
	Space   [16]byte
	Offer   [16]byte
	Amount  *big.Int
	Details string
	State   uint8
}, error) {
	return _Mit-raStorage.Contract.Hits(&_Mit-raStorage.CallOpts, arg0)
}

// Hits is a free data retrieval call binding the contract method 0x9ee3ad44.
//
// Solidity: function hits( bytes16) constant returns(created uint256, hitType uint8, session bytes16, space bytes16, offer bytes16, amount uint256, details string, state uint8)
func (_Mit-raStorage *Mit-raStorageCallerSession) Hits(arg0 [16]byte) (struct {
	Created *big.Int
	HitType uint8
	Session [16]byte
	Space   [16]byte
	Offer   [16]byte
	Amount  *big.Int
	Details string
	State   uint8
}, error) {
	return _Mit-raStorage.Contract.Hits(&_Mit-raStorage.CallOpts, arg0)
}

// Offers is a free data retrieval call binding the contract method 0xc32d869b.
//
// Solidity: function offers( bytes16) constant returns(created uint256, owner bytes16, name string, hitPrice uint256, actionPrice uint256, details string, state uint8)
func (_Mit-raStorage *Mit-raStorageCaller) Offers(opts *bind.CallOpts, arg0 [16]byte) (struct {
	Created     *big.Int
	Owner       [16]byte
	Name        string
	HitPrice    *big.Int
	ActionPrice *big.Int
	Details     string
	State       uint8
}, error) {
	ret := new(struct {
		Created     *big.Int
		Owner       [16]byte
		Name        string
		HitPrice    *big.Int
		ActionPrice *big.Int
		Details     string
		State       uint8
	})
	out := ret
	err := _Mit-raStorage.contract.Call(opts, out, "offers", arg0)
	return *ret, err
}

// Offers is a free data retrieval call binding the contract method 0xc32d869b.
//
// Solidity: function offers( bytes16) constant returns(created uint256, owner bytes16, name string, hitPrice uint256, actionPrice uint256, details string, state uint8)
func (_Mit-raStorage *Mit-raStorageSession) Offers(arg0 [16]byte) (struct {
	Created     *big.Int
	Owner       [16]byte
	Name        string
	HitPrice    *big.Int
	ActionPrice *big.Int
	Details     string
	State       uint8
}, error) {
	return _Mit-raStorage.Contract.Offers(&_Mit-raStorage.CallOpts, arg0)
}

// Offers is a free data retrieval call binding the contract method 0xc32d869b.
//
// Solidity: function offers( bytes16) constant returns(created uint256, owner bytes16, name string, hitPrice uint256, actionPrice uint256, details string, state uint8)
func (_Mit-raStorage *Mit-raStorageCallerSession) Offers(arg0 [16]byte) (struct {
	Created     *big.Int
	Owner       [16]byte
	Name        string
	HitPrice    *big.Int
	ActionPrice *big.Int
	Details     string
	State       uint8
}, error) {
	return _Mit-raStorage.Contract.Offers(&_Mit-raStorage.CallOpts, arg0)
}

// SystemOwner is a free data retrieval call binding the contract method 0x33779254.
//
// Solidity: function systemOwner() constant returns(address)
func (_Mit-raStorage *Mit-raStorageCaller) SystemOwner(opts *bind.CallOpts) (common.Address, error) {
	var (
		ret0 = new(common.Address)
	)
	out := ret0
	err := _Mit-raStorage.contract.Call(opts, out, "systemOwner")
	return *ret0, err
}

// SystemOwner is a free data retrieval call binding the contract method 0x33779254.
//
// Solidity: function systemOwner() constant returns(address)
func (_Mit-raStorage *Mit-raStorageSession) SystemOwner() (common.Address, error) {
	return _Mit-raStorage.Contract.SystemOwner(&_Mit-raStorage.CallOpts)
}

// SystemOwner is a free data retrieval call binding the contract method 0x33779254.
//
// Solidity: function systemOwner() constant returns(address)
func (_Mit-raStorage *Mit-raStorageCallerSession) SystemOwner() (common.Address, error) {
	return _Mit-raStorage.Contract.SystemOwner(&_Mit-raStorage.CallOpts)
}

// Users is a free data retrieval call binding the contract method 0x7520dd14.
//
// Solidity: function users( bytes16) constant returns(created uint256, owner address, role uint8, name string, details string, rank uint8, state uint8)
func (_Mit-raStorage *Mit-raStorageCaller) Users(opts *bind.CallOpts, arg0 [16]byte) (struct {
	Created *big.Int
	Owner   common.Address
	Role    uint8
	Name    string
	Details string
	Rank    uint8
	State   uint8
}, error) {
	ret := new(struct {
		Created *big.Int
		Owner   common.Address
		Role    uint8
		Name    string
		Details string
		Rank    uint8
		State   uint8
	})
	out := ret
	err := _Mit-raStorage.contract.Call(opts, out, "users", arg0)
	return *ret, err
}

// Users is a free data retrieval call binding the contract method 0x7520dd14.
//
// Solidity: function users( bytes16) constant returns(created uint256, owner address, role uint8, name string, details string, rank uint8, state uint8)
func (_Mit-raStorage *Mit-raStorageSession) Users(arg0 [16]byte) (struct {
	Created *big.Int
	Owner   common.Address
	Role    uint8
	Name    string
	Details string
	Rank    uint8
	State   uint8
}, error) {
	return _Mit-raStorage.Contract.Users(&_Mit-raStorage.CallOpts, arg0)
}

// Users is a free data retrieval call binding the contract method 0x7520dd14.
//
// Solidity: function users( bytes16) constant returns(created uint256, owner address, role uint8, name string, details string, rank uint8, state uint8)
func (_Mit-raStorage *Mit-raStorageCallerSession) Users(arg0 [16]byte) (struct {
	Created *big.Int
	Owner   common.Address
	Role    uint8
	Name    string
	Details string
	Rank    uint8
	State   uint8
}, error) {
	return _Mit-raStorage.Contract.Users(&_Mit-raStorage.CallOpts, arg0)
}

// SetAdSpace is a paid mutator transaction binding the contract method 0x7e4a3d4f.
//
// Solidity: function setAdSpace(id bytes16, owner bytes16, name string, url string, details string, categories uint16[], state uint8) returns()
func (_Mit-raStorage *Mit-raStorageTransactor) SetAdSpace(opts *bind.TransactOpts, id [16]byte, owner [16]byte, name string, url string, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raStorage.contract.Transact(opts, "setAdSpace", id, owner, name, url, details, categories, state)
}

// SetAdSpace is a paid mutator transaction binding the contract method 0x7e4a3d4f.
//
// Solidity: function setAdSpace(id bytes16, owner bytes16, name string, url string, details string, categories uint16[], state uint8) returns()
func (_Mit-raStorage *Mit-raStorageSession) SetAdSpace(id [16]byte, owner [16]byte, name string, url string, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.SetAdSpace(&_Mit-raStorage.TransactOpts, id, owner, name, url, details, categories, state)
}

// SetAdSpace is a paid mutator transaction binding the contract method 0x7e4a3d4f.
//
// Solidity: function setAdSpace(id bytes16, owner bytes16, name string, url string, details string, categories uint16[], state uint8) returns()
func (_Mit-raStorage *Mit-raStorageTransactorSession) SetAdSpace(id [16]byte, owner [16]byte, name string, url string, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.SetAdSpace(&_Mit-raStorage.TransactOpts, id, owner, name, url, details, categories, state)
}

// SetHit is a paid mutator transaction binding the contract method 0xff2e6ec4.
//
// Solidity: function setHit(id bytes16, hitType uint8, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raStorage *Mit-raStorageTransactor) SetHit(opts *bind.TransactOpts, id [16]byte, hitType uint8, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raStorage.contract.Transact(opts, "setHit", id, hitType, session, space, offer, amount, details, categories, state)
}

// SetHit is a paid mutator transaction binding the contract method 0xff2e6ec4.
//
// Solidity: function setHit(id bytes16, hitType uint8, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raStorage *Mit-raStorageSession) SetHit(id [16]byte, hitType uint8, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.SetHit(&_Mit-raStorage.TransactOpts, id, hitType, session, space, offer, amount, details, categories, state)
}

// SetHit is a paid mutator transaction binding the contract method 0xff2e6ec4.
//
// Solidity: function setHit(id bytes16, hitType uint8, session bytes16, space bytes16, offer bytes16, amount uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raStorage *Mit-raStorageTransactorSession) SetHit(id [16]byte, hitType uint8, session [16]byte, space [16]byte, offer [16]byte, amount *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.SetHit(&_Mit-raStorage.TransactOpts, id, hitType, session, space, offer, amount, details, categories, state)
}

// SetOffer is a paid mutator transaction binding the contract method 0xf26b7f9b.
//
// Solidity: function setOffer(id bytes16, owner bytes16, name string, hitPrice uint256, actionPrice uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raStorage *Mit-raStorageTransactor) SetOffer(opts *bind.TransactOpts, id [16]byte, owner [16]byte, name string, hitPrice *big.Int, actionPrice *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raStorage.contract.Transact(opts, "setOffer", id, owner, name, hitPrice, actionPrice, details, categories, state)
}

// SetOffer is a paid mutator transaction binding the contract method 0xf26b7f9b.
//
// Solidity: function setOffer(id bytes16, owner bytes16, name string, hitPrice uint256, actionPrice uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raStorage *Mit-raStorageSession) SetOffer(id [16]byte, owner [16]byte, name string, hitPrice *big.Int, actionPrice *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.SetOffer(&_Mit-raStorage.TransactOpts, id, owner, name, hitPrice, actionPrice, details, categories, state)
}

// SetOffer is a paid mutator transaction binding the contract method 0xf26b7f9b.
//
// Solidity: function setOffer(id bytes16, owner bytes16, name string, hitPrice uint256, actionPrice uint256, details string, categories uint16[], state uint8) returns()
func (_Mit-raStorage *Mit-raStorageTransactorSession) SetOffer(id [16]byte, owner [16]byte, name string, hitPrice *big.Int, actionPrice *big.Int, details string, categories []uint16, state uint8) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.SetOffer(&_Mit-raStorage.TransactOpts, id, owner, name, hitPrice, actionPrice, details, categories, state)
}

// SetSystemOwner is a paid mutator transaction binding the contract method 0x621eb9a2.
//
// Solidity: function setSystemOwner(systemOwnerAddress address) returns()
func (_Mit-raStorage *Mit-raStorageTransactor) SetSystemOwner(opts *bind.TransactOpts, systemOwnerAddress common.Address) (*types.Transaction, error) {
	return _Mit-raStorage.contract.Transact(opts, "setSystemOwner", systemOwnerAddress)
}

// SetSystemOwner is a paid mutator transaction binding the contract method 0x621eb9a2.
//
// Solidity: function setSystemOwner(systemOwnerAddress address) returns()
func (_Mit-raStorage *Mit-raStorageSession) SetSystemOwner(systemOwnerAddress common.Address) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.SetSystemOwner(&_Mit-raStorage.TransactOpts, systemOwnerAddress)
}

// SetSystemOwner is a paid mutator transaction binding the contract method 0x621eb9a2.
//
// Solidity: function setSystemOwner(systemOwnerAddress address) returns()
func (_Mit-raStorage *Mit-raStorageTransactorSession) SetSystemOwner(systemOwnerAddress common.Address) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.SetSystemOwner(&_Mit-raStorage.TransactOpts, systemOwnerAddress)
}

// SetUser is a paid mutator transaction binding the contract method 0x4034aad9.
//
// Solidity: function setUser(id bytes16, owner address, role uint8, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raStorage *Mit-raStorageTransactor) SetUser(opts *bind.TransactOpts, id [16]byte, owner common.Address, role uint8, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raStorage.contract.Transact(opts, "setUser", id, owner, role, name, details, rank, state)
}

// SetUser is a paid mutator transaction binding the contract method 0x4034aad9.
//
// Solidity: function setUser(id bytes16, owner address, role uint8, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raStorage *Mit-raStorageSession) SetUser(id [16]byte, owner common.Address, role uint8, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.SetUser(&_Mit-raStorage.TransactOpts, id, owner, role, name, details, rank, state)
}

// SetUser is a paid mutator transaction binding the contract method 0x4034aad9.
//
// Solidity: function setUser(id bytes16, owner address, role uint8, name string, details string, rank uint8, state uint8) returns()
func (_Mit-raStorage *Mit-raStorageTransactorSession) SetUser(id [16]byte, owner common.Address, role uint8, name string, details string, rank uint8, state uint8) (*types.Transaction, error) {
	return _Mit-raStorage.Contract.SetUser(&_Mit-raStorage.TransactOpts, id, owner, role, name, details, rank, state)
}

# vscode-js-react-snippets-cheat-sheet
VS Code Snippets List for Javascript and React

## JS and React Snippets Cheat Sheet

### Import and export (JavaScript (ES6) snippets)

| Trigger | Content                                                                                                |
| ------: | ------------------------------------------------------------------------------------------------------ |
| `imp→`  | imports entire module `import fs from 'fs';`                                                           |
| `imn→`  | imports entire module without module name `import 'animate.css'`                                       |
| `imd→`  | imports only a portion of the module using destructing `import {rename} from 'fs';`                    |
| `ime→`  | imports everything as alias from the module `import * as localAlias from 'fs';`                        |
| `ima→`  | imports only a portion of the module as alias `import { rename as localRename } from 'fs';`            |
| `rqr→`  | require package `require('');`                                                                         |
| `mde→`  | default module.exports `module.exports = {};`                                                          |
| `enf→`  | exports name function `export const log = (parameter) => { console.log(parameter);};`                  |
| `edf→`  | exports default function `export default (parameter) => { console.log(parameter);};`                   |
| `ecl→`  | exports default class `export default class Calculator { };`                                           |
| `ece→`  | exports default class by extending a base one `export default class Calculator extends BaseClass { };` |
| `exp→`  | export default moduleName                                                                              |
| `exd→`  | export { destructuredModule } from 'module'                                                            |
| `exa→`  | export { originalName as aliasName} from 'module'                                                      |

### Class helpers (JavaScript (ES6) snippets)

| Trigger | Content                                                        |
| ------: | -------------------------------------------------------------- |
| `con→`  | adds default constructor in the class `constructor() {}`       |
| `met→`  | creates a method inside a class `add() {}`                     |
| `pge→`  | creates a getter property `get propertyName() {return value;}` |
| `pse→`  | creates a setter property `set propertyName(value) {}`         |
| `cmmb→` | comment block                                                  |

### Various methods (JavaScript (ES6) snippets)

| Trigger      | Content                                                                              |
| -----------: | ------------------------------------------------------------------------------------ |
| `fre→`       | forEach loop in ES6 syntax `array.forEach(currentItem => {})`                        |
| `fof→`       | for ... of loop `for(const item of object) {}`                                       |
| `fin→`       | for ... in loop `for(const item in object) {}`                                       |
| `anfn→`      | creates an anonymous function `(params) => {}`                                       |
| `nfn→`       | creates a named function `const add = (params) => {}`                                |
| `dob→`       | destructing object syntax `const {rename} = fs`                                      |
| `dar→`       | destructing array syntax `const [first, second] = [1,2]`                             |
| `sti→`       | set interval helper method `setInterval(() => {});`                                  |
| `sto→`       | set timeout helper method `setTimeout(() => {});`                                    |
| `prom→`      | creates a new Promise `return new Promise((resolve, reject) => {});`                 |
| `thenCatch→` | adds then and catch declaration to a promise `.then((res) => {).catch((err) => {});` |

### React (ES7 React/Redux/React-Native/JS snippets)

| Prefix      | Method                                                                            |
| ----------: | --------------------------------------------------------------------------------- |
| `imr→`      | import React from 'react'                                                         |
| `imrc→`     | import React, { Component } from 'react'                                          |
| `imrcp→`    | import React, { Component } from 'react' & import PropTypes from 'prop-types'     |
| `imrpc→`    | import React, { PureComponent } from 'react'                                      |
| `imrpcp→`   | import React, { PureComponent } from 'react' & import PropTypes from 'prop-types' |
| `impt→`     | import PropTypes from 'prop-types'                                                |
| `redux→`    | import { connect } from 'react-redux'                                             |
| `rconst→`   | constructor(props) with this.state                                                |
| `rconc→`    | constructor(props, context) with this.state                                       |
| `est→`      | this.state = { }                                                                  |
| `cwm→`      | componentWillMount = () => { } **DEPRECATED!!!**                                  |
| `cdm→`      | componentDidMount = () => { }                                                     |
| `cwr→`      | componentWillReceiveProps = (nextProps) => { } **DEPRECATED!!!**                  |
| `scu→`      | shouldComponentUpdate = (nextProps, nextState) => { }                             |
| `cwup→`     | componentWillUpdate = (nextProps, nextState) => { } **DEPRECATED!!!**             |
| `cdup→`     | componentDidUpdate = (prevProps, prevState) => { }                                |
| `cwun→`     | componentWillUnmount = () => { }                                                  |
| `cwun→`     | componentWillUnmount = () => { }                                                  |
| `gdsfp→`    | static getDerivedStateFromProps(nextProps, prevState) { }                         |
| `gsbu→`     | getSnapshotBeforeUpdate = (prevProps, prevState) => { }                           |
| `ren→`      | render() { return( ) }                                                            |
| `sst→`      | this.setState({ })                                                                |
| `ssf→`      | this.setState((state, props) => return { })                                       |
| `props→`    | this.props.propName                                                               |
| `state→`    | this.state.stateName                                                              |
| `rcontext→` | const ${1:contextName} = React.createContext()                                    |
| `cref→`     | this.${1:refName}Ref = React.createRef()                                          |
| `fref→`     | const ref = React.createRef()                                                     |
| `bnd→`      | this.methodName = this.methodName.bind(this)                                      |
| `cp→`       | const { } = this.props                                                            |
| `cs→`       | const { } = this.state                                                            |

### React Components (ES7 React/Redux/React-Native/JS snippets)

| Prefix      | Method                                                         |
| ----------: | -------------------------------------------------------------- |
| `rcc→`      | Export Default React Component Class                           |
| `rce→`      | React Component Class                                          |
| `rcep→`     | React Component Class with PropTypes                           |
| `rpc→`      | React PureComponent Class                                      |
| `rpcp→`     | React PureComponent Class with PropTypes                       |
| `rccp→`     | React Component Class with PropTypes                           |
| `rfe→`      | React Functional Component (ES6) Export Default                |
| `rfep→`     | React Functional Component (ES6) with PropTypes Export Default |
| `rfc→`      | Export Default React Functional Component (ES6)                |
| `rfcp→`     | Export Default React Functional Component (ES6) with PropTypes |
| `rcredux→`  | React Component Class with Redux                               |
| `reduxmap→` | Generate mapStateToProps and mapDispatchToProps                |

### Components (Reactjs code snippets)

| Trigger  | Content                                                          |
| -------: | ---------------------------------------------------------------- |
| `rcc→`   | Class Component Skeleton                                         |
| `rrc→`   | Class Component Skeleton with react-redux connect                |
| `rccp→`  | Class Component Skeleton with prop types after the class         |
| `rcjc→`  | Class Component Skeleton without import and default export lines |
| `rcfc→`  | Class Component Skeleton that contains all the lifecycle methods |
| `rwwd→`  | Class Component without import statements                        |
| `rpc→`   | Class Pure component skeleton with prop types after the class    |
| `rsc→`   | Stateless Component Skeleton                                     |
| `rscp→`  | Stateless Component with prop types skeleton                     |
| `rsf→`   | Stateless named function skeleton                                |
| `rsfp→`  | Stateless named function with prop types skeleton                |
| `rpt→`   | Empty propTypes declaration                                      |
| `rdp→`   | Empty defaultProps declaration                                   |
| `con→`   | Class default constructor with props                             |
| `conc→`  | Class default constructor with props and context                 |
| `est→`   | Empty state object                                               |
| `cwm→`   | componentWillMount method                                        |
| `cdm→`   | componentDidMount method                                         |
| `cwr→`   | componentWillReceiveProps method                                 |
| `scu→`   | shouldComponentUpdate method                                     |
| `cwup→`  | componentWillUpdate method                                       |
| `cdup→`  | componentDidUpdate method                                        |
| `cwun→`  | componentWillUnmount method                                      |
| `gsbu→`  | getSnapshotBeforeUpdate method                                   |
| `gdsfp→` | static getDerivedStateFromProps method                           |
| `cdc→`   | componentDidCatch method                                         |
| `ren→`   | render method                                                    |
| `sst→`   | this.setState with object as parameter                           |
| `ssf→`   | this.setState with function as parameter                         |
| `props→` | this.props                                                       |
| `state→` | this.state                                                       |
| `bnd→`   | binds the this of method inside the constructor                  |

### Redux (ES7 React/Redux/React-Native/JS snippets)

| Prefix       | Method                  |
| -----------: | ----------------------- |
| `rxaction→`  | redux action template   |
| `rxconst→`   | export const $1 = '$1'  |
| `rxreducer→` | redux reducer template  |
| `rxselect→`  | redux selector template |

### PropTypes (ES7 React/Redux/React-Native/JS snippets and Reactjs code snippets)

| Prefix    | Method                                                                             |
| --------: | ---------------------------------------------------------------------------------- |
| `pta→`    | PropTypes.array                                                                    |
| `ptar→`   | PropTypes.array.isRequired                                                         |
| `ptb→`    | PropTypes.bool                                                                     |
| `ptbr→`   | PropTypes.bool.isRequired                                                          |
| `ptf→`    | PropTypes.func                                                                     |
| `ptfr→`   | PropTypes.func.isRequired                                                          |
| `ptn→`    | PropTypes.number                                                                   |
| `ptnr→`   | PropTypes.number.isRequired                                                        |
| `pto→`    | PropTypes.object                                                                   |
| `ptor→`   | PropTypes.object.isRequired                                                        |
| `pts→`    | PropTypes.string                                                                   |
| `ptsr→`   | PropTypes.string.isRequired                                                        |
| `ptnd→`   | PropTypes.node                                                                     |
| `ptndr→`  | PropTypes.node.isRequired                                                          |
| `ptel→`   | PropTypes.element                                                                  |
| `ptelr→`  | PropTypes.element.isRequired                                                       |
| `pti→`    | PropTypes.instanceOf(name)                                                         |
| `ptir→`   | PropTypes.instanceOf(name).isRequired                                              |
| `pte→`    | PropTypes.oneOf([name])                                                            |
| `pter→`   | PropTypes.oneOf([name]).isRequired                                                 |
| `ptet→`   | PropTypes.oneOfType([name])                                                        |
| `ptetr→`  | PropTypes.oneOfType([name]).isRequired                                             |
| `ptao→`   | PropTypes.arrayOf(name)                                                            |
| `ptaor→`  | PropTypes.arrayOf(name).isRequired                                                 |
| `ptoo→`   | PropTypes.objectOf(name)                                                           |
| `ptoor→`  | PropTypes.objectOf(name).isRequired                                                |
| `ptsh→`   | PropTypes.shape({ })                                                               |
| `ptshr→`  | PropTypes.shape({ }).isRequired                                                    |
| `ptoos→`  | PropTypes.objectOf(PropTypes.shape()),                                             |
| `ptoosr→` | PropTypes.objectOf(PropTypes.shape()).isRequired,                                  |
| `ptsh→`   | PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}),            |
| `ptshr→`  | PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}).isRequired, |
| `ptany→`  | PropTypes.any                                                                      |
| `ptypes→` | static propTypes = {}                                                              |

### Console methods (JavaScript (ES6) snippets)

| Trigger | Content                                                         |
| ------: | --------------------------------------------------------------- |
| `clg→`  | console log `console.log(object)`                               |
| `clo→`  | console log object with name `console.log('object :', object);` |
| `cer→`  | console error `console.error(object)`                           |
| `cwa→`  | console warn `console.warn`                                     |
| `cin→`  | console info `console.info`                                     |
| `cgr→`  | console group `console.group(label)`                            |
| `cge→`  | console groupEnd `console.groupEnd()`                           |
| `cco→`  | console count `console.count(label)`                            |
| `cas→`  | console alert method `console.assert(expression, object)`       |
| `cdi→`  | console dir `console.dir`                                       |
| `ctr→`  | console trace `console.trace(object)`                           |
| `clt→`  | console table `console.table`                                   |
| `ccl→`  | console clear `console.clear()`                                 |

### Tests and others (ES7 React/Redux/React-Native/JS snippets)

| Prefix      | Method                           |
| ----------: | -------------------------------- |
| `desc→`     | describe('$1', () => { $2 })     |
| `test→`     | test('should $1', () => { $2 })  |
| `tit→`      | it('should $1', () => { $2 })    |
| `stest→`    | Test Class                       |
| `sjtest→`   | Test Class                       |
| `sntest→`   | Test Class                       |
| `sctest→`   | Test Class                       |
| `snrtest→`  | Test Class                       |
| `hocredux→` | Connected Higher Order Component |
| `hoc→`      | Higher Order Component           |

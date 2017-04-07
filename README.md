# api documentation for  [seriate (v0.9.0)](http://github.com/leankit-labs/seriate)  [![npm package](https://img.shields.io/npm/v/npmdoc-seriate.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-seriate) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-seriate.svg)](https://travis-ci.org/npmdoc/node-npmdoc-seriate)
#### A cross platform module for Microsoft SQL Server that wraps node-mssql

[![NPM](https://nodei.co/npm/seriate.png?downloads=true)](https://www.npmjs.com/package/seriate)

[![apidoc](https://npmdoc.github.io/node-npmdoc-seriate/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-seriate_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-seriate/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-seriate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-seriate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "LeanKit"
    },
    "bugs": {
        "url": "https://github.com/LeanKit-Labs/seriate/issues"
    },
    "contributors": [
        {
            "name": "Jim Cowart",
            "email": "jim.cowart@leankit.com",
            "url": "http://ifandelse.com"
        },
        {
            "name": "Alex Robson",
            "email": "asrobson@gmail.com",
            "url": "http://nerdventure.io"
        },
        {
            "name": "Ryan Niemeyer",
            "email": "ryan@knockmeout.net",
            "url": "http://knockmeout.net"
        },
        {
            "name": "Brian Edgerton",
            "email": "brian.edgerton@leankit.com"
        },
        {
            "name": "Scott Walters",
            "email": "scott.walters@leankit.com"
        },
        {
            "name": "David Neal",
            "url": "https://github.com/reverentgeek"
        },
        {
            "name": "Calvin Bottoms",
            "url": "https://github.com/calvinb"
        },
        {
            "name": "Josh Bush",
            "url": "https://github.com/digitalbush"
        }
    ],
    "dependencies": {
        "callsite": "^1.0.0",
        "configya": "~0.2.1",
        "lodash": "3.x",
        "machina": "1.x",
        "monologue.js": "~0.3.3",
        "mssql": "~2.3.2",
        "postal": "^1.0.6",
        "when": "3.x",
        "whistlepunk": "^0.3.1",
        "xmldom": "^0.1.22"
    },
    "description": "A cross platform module for Microsoft SQL Server that wraps node-mssql",
    "devDependencies": {
        "biggulp": "~0.2.0",
        "chai": "~2.3.0",
        "chai-as-promised": "~5.0.0",
        "gulp": "~3.9.*",
        "metronic": "^0.2.4",
        "proxyquire": "~1.5.0",
        "sinon": "~1.14.1",
        "sinon-as-promised": "~4.0.0",
        "sinon-chai": "~2.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "6490cacc729b630df40c5fef163ecde26c50001a",
        "tarball": "https://registry.npmjs.org/seriate/-/seriate-0.9.0.tgz"
    },
    "files": [
        "LICENSE",
        "src"
    ],
    "gitHead": "2b61b2f4400f23c564285dc608efaf406ad9be4b",
    "homepage": "http://github.com/leankit-labs/seriate",
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "arobson",
            "email": "asrobson@gmail.com"
        },
        {
            "name": "brian_edgerton",
            "email": "brian.edgerton@leankit.com"
        },
        {
            "name": "calvin.bottoms",
            "email": "calvin.bottoms@gmail.com"
        },
        {
            "name": "digitalbush",
            "email": "josh@digitalbush.com"
        },
        {
            "name": "ifandelse",
            "email": "jim@ifandelse.com"
        },
        {
            "name": "prestaul",
            "email": "mpdunlap@gmail.com"
        },
        {
            "name": "rniemeyer",
            "email": "rniemeyer@gmail.com"
        },
        {
            "name": "ryexley",
            "email": "bob@yexley.net"
        }
    ],
    "name": "seriate",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "https://registry.npmjs.org/"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/LeanKit-Labs/seriate.git"
    },
    "scripts": {
        "example": "node ./example/example.js",
        "test": "gulp test"
    },
    "version": "0.9.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module seriate](#apidoc.module.seriate)
1.  [function <span class="apidocSignatureSpan">seriate.</span>BIGINT ()](#apidoc.element.seriate.BIGINT)
1.  [function <span class="apidocSignatureSpan">seriate.</span>BINARY (length)](#apidoc.element.seriate.BINARY)
1.  [function <span class="apidocSignatureSpan">seriate.</span>BIT ()](#apidoc.element.seriate.BIT)
1.  [function <span class="apidocSignatureSpan">seriate.</span>BigInt ()](#apidoc.element.seriate.BigInt)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Binary (length)](#apidoc.element.seriate.Binary)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Bit ()](#apidoc.element.seriate.Bit)
1.  [function <span class="apidocSignatureSpan">seriate.</span>CHAR (length)](#apidoc.element.seriate.CHAR)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Char (length)](#apidoc.element.seriate.Char)
1.  [function <span class="apidocSignatureSpan">seriate.</span>DATE ()](#apidoc.element.seriate.DATE)
1.  [function <span class="apidocSignatureSpan">seriate.</span>DATETIME ()](#apidoc.element.seriate.DATETIME)
1.  [function <span class="apidocSignatureSpan">seriate.</span>DATETIME2 (scale)](#apidoc.element.seriate.DATETIME2)
1.  [function <span class="apidocSignatureSpan">seriate.</span>DATETIMEOFFSET (scale)](#apidoc.element.seriate.DATETIMEOFFSET)
1.  [function <span class="apidocSignatureSpan">seriate.</span>DECIMAL (precision, scale)](#apidoc.element.seriate.DECIMAL)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Date ()](#apidoc.element.seriate.Date)
1.  [function <span class="apidocSignatureSpan">seriate.</span>DateTime ()](#apidoc.element.seriate.DateTime)
1.  [function <span class="apidocSignatureSpan">seriate.</span>DateTime2 (scale)](#apidoc.element.seriate.DateTime2)
1.  [function <span class="apidocSignatureSpan">seriate.</span>DateTimeOffset (scale)](#apidoc.element.seriate.DateTimeOffset)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Decimal (precision, scale)](#apidoc.element.seriate.Decimal)
1.  [function <span class="apidocSignatureSpan">seriate.</span>FLOAT ()](#apidoc.element.seriate.FLOAT)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Float ()](#apidoc.element.seriate.Float)
1.  [function <span class="apidocSignatureSpan">seriate.</span>GEOGRAPHY ()](#apidoc.element.seriate.GEOGRAPHY)
1.  [function <span class="apidocSignatureSpan">seriate.</span>GEOMETRY ()](#apidoc.element.seriate.GEOMETRY)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Geography ()](#apidoc.element.seriate.Geography)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Geometry ()](#apidoc.element.seriate.Geometry)
1.  [function <span class="apidocSignatureSpan">seriate.</span>IMAGE ()](#apidoc.element.seriate.IMAGE)
1.  [function <span class="apidocSignatureSpan">seriate.</span>INT ()](#apidoc.element.seriate.INT)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Image ()](#apidoc.element.seriate.Image)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Int ()](#apidoc.element.seriate.Int)
1.  [function <span class="apidocSignatureSpan">seriate.</span>MONEY ()](#apidoc.element.seriate.MONEY)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Money ()](#apidoc.element.seriate.Money)
1.  [function <span class="apidocSignatureSpan">seriate.</span>NCHAR (length)](#apidoc.element.seriate.NCHAR)
1.  [function <span class="apidocSignatureSpan">seriate.</span>NChar (length)](#apidoc.element.seriate.NChar)
1.  [function <span class="apidocSignatureSpan">seriate.</span>NTEXT ()](#apidoc.element.seriate.NTEXT)
1.  [function <span class="apidocSignatureSpan">seriate.</span>NText ()](#apidoc.element.seriate.NText)
1.  [function <span class="apidocSignatureSpan">seriate.</span>NUMERIC (precision, scale)](#apidoc.element.seriate.NUMERIC)
1.  [function <span class="apidocSignatureSpan">seriate.</span>NVARCHAR (length)](#apidoc.element.seriate.NVARCHAR)
1.  [function <span class="apidocSignatureSpan">seriate.</span>NVarChar (length)](#apidoc.element.seriate.NVarChar)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Numeric (precision, scale)](#apidoc.element.seriate.Numeric)
1.  [function <span class="apidocSignatureSpan">seriate.</span>REAL ()](#apidoc.element.seriate.REAL)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Real ()](#apidoc.element.seriate.Real)
1.  [function <span class="apidocSignatureSpan">seriate.</span>SMALLDATETIME ()](#apidoc.element.seriate.SMALLDATETIME)
1.  [function <span class="apidocSignatureSpan">seriate.</span>SMALLINT ()](#apidoc.element.seriate.SMALLINT)
1.  [function <span class="apidocSignatureSpan">seriate.</span>SMALLMONEY ()](#apidoc.element.seriate.SMALLMONEY)
1.  [function <span class="apidocSignatureSpan">seriate.</span>SmallDateTime ()](#apidoc.element.seriate.SmallDateTime)
1.  [function <span class="apidocSignatureSpan">seriate.</span>SmallInt ()](#apidoc.element.seriate.SmallInt)
1.  [function <span class="apidocSignatureSpan">seriate.</span>SmallMoney ()](#apidoc.element.seriate.SmallMoney)
1.  [function <span class="apidocSignatureSpan">seriate.</span>TEXT ()](#apidoc.element.seriate.TEXT)
1.  [function <span class="apidocSignatureSpan">seriate.</span>TIME (scale)](#apidoc.element.seriate.TIME)
1.  [function <span class="apidocSignatureSpan">seriate.</span>TINYINT ()](#apidoc.element.seriate.TINYINT)
1.  [function <span class="apidocSignatureSpan">seriate.</span>TVP (tvpType)](#apidoc.element.seriate.TVP)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Text ()](#apidoc.element.seriate.Text)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Time (scale)](#apidoc.element.seriate.Time)
1.  [function <span class="apidocSignatureSpan">seriate.</span>TinyInt ()](#apidoc.element.seriate.TinyInt)
1.  [function <span class="apidocSignatureSpan">seriate.</span>UDT ()](#apidoc.element.seriate.UDT)
1.  [function <span class="apidocSignatureSpan">seriate.</span>UNIQUEIDENTIFIER ()](#apidoc.element.seriate.UNIQUEIDENTIFIER)
1.  [function <span class="apidocSignatureSpan">seriate.</span>UniqueIdentifier ()](#apidoc.element.seriate.UniqueIdentifier)
1.  [function <span class="apidocSignatureSpan">seriate.</span>VARBINARY (length)](#apidoc.element.seriate.VARBINARY)
1.  [function <span class="apidocSignatureSpan">seriate.</span>VARCHAR (length)](#apidoc.element.seriate.VARCHAR)
1.  [function <span class="apidocSignatureSpan">seriate.</span>VarBinary (length)](#apidoc.element.seriate.VarBinary)
1.  [function <span class="apidocSignatureSpan">seriate.</span>VarChar (length)](#apidoc.element.seriate.VarChar)
1.  [function <span class="apidocSignatureSpan">seriate.</span>XML ()](#apidoc.element.seriate.XML)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Xml ()](#apidoc.element.seriate.Xml)
1.  [function <span class="apidocSignatureSpan">seriate.</span>addConnection ( config )](#apidoc.element.seriate.addConnection)
1.  [function <span class="apidocSignatureSpan">seriate.</span>closeConnection ( config )](#apidoc.element.seriate.closeConnection)
1.  [function <span class="apidocSignatureSpan">seriate.</span>emit ( topic, data )](#apidoc.element.seriate.emit)
1.  [function <span class="apidocSignatureSpan">seriate.</span>execute ( connection, queryOptions )](#apidoc.element.seriate.execute)
1.  [function <span class="apidocSignatureSpan">seriate.</span>executeTransaction ( connection, queryOptions )](#apidoc.element.seriate.executeTransaction)
1.  [function <span class="apidocSignatureSpan">seriate.</span>first ()](#apidoc.element.seriate.first)
1.  [function <span class="apidocSignatureSpan">seriate.</span>fromFile ( p )](#apidoc.element.seriate.fromFile)
1.  [function <span class="apidocSignatureSpan">seriate.</span>getEnvelope ( topic, data )](#apidoc.element.seriate.getEnvelope)
1.  [function <span class="apidocSignatureSpan">seriate.</span>getPlainContext ( connection )](#apidoc.element.seriate.getPlainContext)
1.  [function <span class="apidocSignatureSpan">seriate.</span>getTransactionContext ( connection )](#apidoc.element.seriate.getTransactionContext)
1.  [function <span class="apidocSignatureSpan">seriate.</span>off ( topic, context )](#apidoc.element.seriate.off)
1.  [function <span class="apidocSignatureSpan">seriate.</span>on ( topic, callback )](#apidoc.element.seriate.on)
1.  [function <span class="apidocSignatureSpan">seriate.</span>once ( topic, callback )](#apidoc.element.seriate.once)
1.  [function <span class="apidocSignatureSpan">seriate.</span>resetConnections ()](#apidoc.element.seriate.resetConnections)
1.  [function <span class="apidocSignatureSpan">seriate.</span>setDefault ( config )](#apidoc.element.seriate.setDefault)
1.  [function <span class="apidocSignatureSpan">seriate.</span>setDefaultConfig ( config )](#apidoc.element.seriate.setDefaultConfig)
1.  [function <span class="apidocSignatureSpan">seriate.</span>useMetrics ( metrics, namespace )](#apidoc.element.seriate.useMetrics)
1.  number <span class="apidocSignatureSpan">seriate.</span>MAX
1.  number <span class="apidocSignatureSpan">seriate.</span>READ_COMMITTED
1.  number <span class="apidocSignatureSpan">seriate.</span>READ_UNCOMMITTED
1.  number <span class="apidocSignatureSpan">seriate.</span>REPEATABLE_READ
1.  number <span class="apidocSignatureSpan">seriate.</span>SERIALIZABLE
1.  number <span class="apidocSignatureSpan">seriate.</span>SNAPSHOT
1.  object <span class="apidocSignatureSpan">seriate.</span>connections
1.  object <span class="apidocSignatureSpan">seriate.</span>utils

#### [module seriate.BigInt](#apidoc.module.seriate.BigInt)
1.  [function <span class="apidocSignatureSpan">seriate.</span>BigInt ()](#apidoc.element.seriate.BigInt.BigInt)
1.  [function <span class="apidocSignatureSpan">seriate.BigInt.</span>inspect ()](#apidoc.element.seriate.BigInt.inspect)
1.  string <span class="apidocSignatureSpan">seriate.BigInt.</span>declaration

#### [module seriate.Binary](#apidoc.module.seriate.Binary)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Binary (length)](#apidoc.element.seriate.Binary.Binary)
1.  [function <span class="apidocSignatureSpan">seriate.Binary.</span>inspect ()](#apidoc.element.seriate.Binary.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Binary.</span>declaration

#### [module seriate.Bit](#apidoc.module.seriate.Bit)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Bit ()](#apidoc.element.seriate.Bit.Bit)
1.  [function <span class="apidocSignatureSpan">seriate.Bit.</span>inspect ()](#apidoc.element.seriate.Bit.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Bit.</span>declaration

#### [module seriate.Char](#apidoc.module.seriate.Char)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Char (length)](#apidoc.element.seriate.Char.Char)
1.  [function <span class="apidocSignatureSpan">seriate.Char.</span>inspect ()](#apidoc.element.seriate.Char.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Char.</span>declaration

#### [module seriate.Date](#apidoc.module.seriate.Date)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Date ()](#apidoc.element.seriate.Date.Date)
1.  [function <span class="apidocSignatureSpan">seriate.Date.</span>inspect ()](#apidoc.element.seriate.Date.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Date.</span>declaration

#### [module seriate.DateTime](#apidoc.module.seriate.DateTime)
1.  [function <span class="apidocSignatureSpan">seriate.</span>DateTime ()](#apidoc.element.seriate.DateTime.DateTime)
1.  [function <span class="apidocSignatureSpan">seriate.DateTime.</span>inspect ()](#apidoc.element.seriate.DateTime.inspect)
1.  string <span class="apidocSignatureSpan">seriate.DateTime.</span>declaration

#### [module seriate.DateTime2](#apidoc.module.seriate.DateTime2)
1.  [function <span class="apidocSignatureSpan">seriate.</span>DateTime2 (scale)](#apidoc.element.seriate.DateTime2.DateTime2)
1.  [function <span class="apidocSignatureSpan">seriate.DateTime2.</span>inspect ()](#apidoc.element.seriate.DateTime2.inspect)
1.  string <span class="apidocSignatureSpan">seriate.DateTime2.</span>declaration

#### [module seriate.DateTimeOffset](#apidoc.module.seriate.DateTimeOffset)
1.  [function <span class="apidocSignatureSpan">seriate.</span>DateTimeOffset (scale)](#apidoc.element.seriate.DateTimeOffset.DateTimeOffset)
1.  [function <span class="apidocSignatureSpan">seriate.DateTimeOffset.</span>inspect ()](#apidoc.element.seriate.DateTimeOffset.inspect)
1.  string <span class="apidocSignatureSpan">seriate.DateTimeOffset.</span>declaration

#### [module seriate.Decimal](#apidoc.module.seriate.Decimal)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Decimal (precision, scale)](#apidoc.element.seriate.Decimal.Decimal)
1.  [function <span class="apidocSignatureSpan">seriate.Decimal.</span>inspect ()](#apidoc.element.seriate.Decimal.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Decimal.</span>declaration

#### [module seriate.Float](#apidoc.module.seriate.Float)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Float ()](#apidoc.element.seriate.Float.Float)
1.  [function <span class="apidocSignatureSpan">seriate.Float.</span>inspect ()](#apidoc.element.seriate.Float.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Float.</span>declaration

#### [module seriate.Geography](#apidoc.module.seriate.Geography)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Geography ()](#apidoc.element.seriate.Geography.Geography)
1.  [function <span class="apidocSignatureSpan">seriate.Geography.</span>inspect ()](#apidoc.element.seriate.Geography.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Geography.</span>declaration

#### [module seriate.Geometry](#apidoc.module.seriate.Geometry)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Geometry ()](#apidoc.element.seriate.Geometry.Geometry)
1.  [function <span class="apidocSignatureSpan">seriate.Geometry.</span>inspect ()](#apidoc.element.seriate.Geometry.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Geometry.</span>declaration

#### [module seriate.Image](#apidoc.module.seriate.Image)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Image ()](#apidoc.element.seriate.Image.Image)
1.  [function <span class="apidocSignatureSpan">seriate.Image.</span>inspect ()](#apidoc.element.seriate.Image.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Image.</span>declaration

#### [module seriate.Int](#apidoc.module.seriate.Int)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Int ()](#apidoc.element.seriate.Int.Int)
1.  [function <span class="apidocSignatureSpan">seriate.Int.</span>inspect ()](#apidoc.element.seriate.Int.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Int.</span>declaration

#### [module seriate.Money](#apidoc.module.seriate.Money)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Money ()](#apidoc.element.seriate.Money.Money)
1.  [function <span class="apidocSignatureSpan">seriate.Money.</span>inspect ()](#apidoc.element.seriate.Money.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Money.</span>declaration

#### [module seriate.NChar](#apidoc.module.seriate.NChar)
1.  [function <span class="apidocSignatureSpan">seriate.</span>NChar (length)](#apidoc.element.seriate.NChar.NChar)
1.  [function <span class="apidocSignatureSpan">seriate.NChar.</span>inspect ()](#apidoc.element.seriate.NChar.inspect)
1.  string <span class="apidocSignatureSpan">seriate.NChar.</span>declaration

#### [module seriate.NText](#apidoc.module.seriate.NText)
1.  [function <span class="apidocSignatureSpan">seriate.</span>NText ()](#apidoc.element.seriate.NText.NText)
1.  [function <span class="apidocSignatureSpan">seriate.NText.</span>inspect ()](#apidoc.element.seriate.NText.inspect)
1.  string <span class="apidocSignatureSpan">seriate.NText.</span>declaration

#### [module seriate.NVarChar](#apidoc.module.seriate.NVarChar)
1.  [function <span class="apidocSignatureSpan">seriate.</span>NVarChar (length)](#apidoc.element.seriate.NVarChar.NVarChar)
1.  [function <span class="apidocSignatureSpan">seriate.NVarChar.</span>inspect ()](#apidoc.element.seriate.NVarChar.inspect)
1.  string <span class="apidocSignatureSpan">seriate.NVarChar.</span>declaration

#### [module seriate.Numeric](#apidoc.module.seriate.Numeric)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Numeric (precision, scale)](#apidoc.element.seriate.Numeric.Numeric)
1.  [function <span class="apidocSignatureSpan">seriate.Numeric.</span>inspect ()](#apidoc.element.seriate.Numeric.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Numeric.</span>declaration

#### [module seriate.Real](#apidoc.module.seriate.Real)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Real ()](#apidoc.element.seriate.Real.Real)
1.  [function <span class="apidocSignatureSpan">seriate.Real.</span>inspect ()](#apidoc.element.seriate.Real.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Real.</span>declaration

#### [module seriate.SmallDateTime](#apidoc.module.seriate.SmallDateTime)
1.  [function <span class="apidocSignatureSpan">seriate.</span>SmallDateTime ()](#apidoc.element.seriate.SmallDateTime.SmallDateTime)
1.  [function <span class="apidocSignatureSpan">seriate.SmallDateTime.</span>inspect ()](#apidoc.element.seriate.SmallDateTime.inspect)
1.  string <span class="apidocSignatureSpan">seriate.SmallDateTime.</span>declaration

#### [module seriate.SmallInt](#apidoc.module.seriate.SmallInt)
1.  [function <span class="apidocSignatureSpan">seriate.</span>SmallInt ()](#apidoc.element.seriate.SmallInt.SmallInt)
1.  [function <span class="apidocSignatureSpan">seriate.SmallInt.</span>inspect ()](#apidoc.element.seriate.SmallInt.inspect)
1.  string <span class="apidocSignatureSpan">seriate.SmallInt.</span>declaration

#### [module seriate.SmallMoney](#apidoc.module.seriate.SmallMoney)
1.  [function <span class="apidocSignatureSpan">seriate.</span>SmallMoney ()](#apidoc.element.seriate.SmallMoney.SmallMoney)
1.  [function <span class="apidocSignatureSpan">seriate.SmallMoney.</span>inspect ()](#apidoc.element.seriate.SmallMoney.inspect)
1.  string <span class="apidocSignatureSpan">seriate.SmallMoney.</span>declaration

#### [module seriate.TVP](#apidoc.module.seriate.TVP)
1.  [function <span class="apidocSignatureSpan">seriate.</span>TVP (tvpType)](#apidoc.element.seriate.TVP.TVP)
1.  [function <span class="apidocSignatureSpan">seriate.TVP.</span>inspect ()](#apidoc.element.seriate.TVP.inspect)
1.  string <span class="apidocSignatureSpan">seriate.TVP.</span>declaration

#### [module seriate.Text](#apidoc.module.seriate.Text)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Text ()](#apidoc.element.seriate.Text.Text)
1.  [function <span class="apidocSignatureSpan">seriate.Text.</span>inspect ()](#apidoc.element.seriate.Text.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Text.</span>declaration

#### [module seriate.Time](#apidoc.module.seriate.Time)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Time (scale)](#apidoc.element.seriate.Time.Time)
1.  [function <span class="apidocSignatureSpan">seriate.Time.</span>inspect ()](#apidoc.element.seriate.Time.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Time.</span>declaration

#### [module seriate.TinyInt](#apidoc.module.seriate.TinyInt)
1.  [function <span class="apidocSignatureSpan">seriate.</span>TinyInt ()](#apidoc.element.seriate.TinyInt.TinyInt)
1.  [function <span class="apidocSignatureSpan">seriate.TinyInt.</span>inspect ()](#apidoc.element.seriate.TinyInt.inspect)
1.  string <span class="apidocSignatureSpan">seriate.TinyInt.</span>declaration

#### [module seriate.UDT](#apidoc.module.seriate.UDT)
1.  [function <span class="apidocSignatureSpan">seriate.</span>UDT ()](#apidoc.element.seriate.UDT.UDT)
1.  [function <span class="apidocSignatureSpan">seriate.UDT.</span>inspect ()](#apidoc.element.seriate.UDT.inspect)
1.  string <span class="apidocSignatureSpan">seriate.UDT.</span>declaration

#### [module seriate.UniqueIdentifier](#apidoc.module.seriate.UniqueIdentifier)
1.  [function <span class="apidocSignatureSpan">seriate.</span>UniqueIdentifier ()](#apidoc.element.seriate.UniqueIdentifier.UniqueIdentifier)
1.  [function <span class="apidocSignatureSpan">seriate.UniqueIdentifier.</span>inspect ()](#apidoc.element.seriate.UniqueIdentifier.inspect)
1.  string <span class="apidocSignatureSpan">seriate.UniqueIdentifier.</span>declaration

#### [module seriate.VarBinary](#apidoc.module.seriate.VarBinary)
1.  [function <span class="apidocSignatureSpan">seriate.</span>VarBinary (length)](#apidoc.element.seriate.VarBinary.VarBinary)
1.  [function <span class="apidocSignatureSpan">seriate.VarBinary.</span>inspect ()](#apidoc.element.seriate.VarBinary.inspect)
1.  string <span class="apidocSignatureSpan">seriate.VarBinary.</span>declaration

#### [module seriate.VarChar](#apidoc.module.seriate.VarChar)
1.  [function <span class="apidocSignatureSpan">seriate.</span>VarChar (length)](#apidoc.element.seriate.VarChar.VarChar)
1.  [function <span class="apidocSignatureSpan">seriate.VarChar.</span>inspect ()](#apidoc.element.seriate.VarChar.inspect)
1.  string <span class="apidocSignatureSpan">seriate.VarChar.</span>declaration

#### [module seriate.Xml](#apidoc.module.seriate.Xml)
1.  [function <span class="apidocSignatureSpan">seriate.</span>Xml ()](#apidoc.element.seriate.Xml.Xml)
1.  [function <span class="apidocSignatureSpan">seriate.Xml.</span>inspect ()](#apidoc.element.seriate.Xml.inspect)
1.  string <span class="apidocSignatureSpan">seriate.Xml.</span>declaration

#### [module seriate.connections](#apidoc.module.seriate.connections)
1.  [function <span class="apidocSignatureSpan">seriate.connections.</span>add ( config )](#apidoc.element.seriate.connections.add)
1.  [function <span class="apidocSignatureSpan">seriate.connections.</span>close ( config )](#apidoc.element.seriate.connections.close)
1.  [function <span class="apidocSignatureSpan">seriate.connections.</span>emit ( topic, data )](#apidoc.element.seriate.connections.emit)
1.  [function <span class="apidocSignatureSpan">seriate.connections.</span>get ( config )](#apidoc.element.seriate.connections.get)
1.  [function <span class="apidocSignatureSpan">seriate.connections.</span>getEnvelope ( topic, data )](#apidoc.element.seriate.connections.getEnvelope)
1.  [function <span class="apidocSignatureSpan">seriate.connections.</span>off ( topic, context )](#apidoc.element.seriate.connections.off)
1.  [function <span class="apidocSignatureSpan">seriate.connections.</span>on ( topic, callback )](#apidoc.element.seriate.connections.on)
1.  [function <span class="apidocSignatureSpan">seriate.connections.</span>once ( topic, callback )](#apidoc.element.seriate.connections.once)
1.  [function <span class="apidocSignatureSpan">seriate.connections.</span>reset ()](#apidoc.element.seriate.connections.reset)
1.  object <span class="apidocSignatureSpan">seriate.connections.</span>_subscriptions
1.  object <span class="apidocSignatureSpan">seriate.connections.</span>state

#### [module seriate.utils](#apidoc.module.seriate.utils)
1.  [function <span class="apidocSignatureSpan">seriate.utils.</span>fromFile ( p )](#apidoc.element.seriate.utils.fromFile)



# <a name="apidoc.module.seriate"></a>[module seriate](#apidoc.module.seriate)

#### <a name="apidoc.element.seriate.BIGINT"></a>[function <span class="apidocSignatureSpan">seriate.</span>BIGINT ()](#apidoc.element.seriate.BIGINT)
- description and source-code
```javascript
BIGINT = function () {
  return {
    type: TYPES.BigInt
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.BINARY"></a>[function <span class="apidocSignatureSpan">seriate.</span>BINARY (length)](#apidoc.element.seriate.BINARY)
- description and source-code
```javascript
BINARY = function (length) {
  return {
    type: TYPES.Binary,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.BIT"></a>[function <span class="apidocSignatureSpan">seriate.</span>BIT ()](#apidoc.element.seriate.BIT)
- description and source-code
```javascript
BIT = function () {
  return {
    type: TYPES.Bit
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.BigInt"></a>[function <span class="apidocSignatureSpan">seriate.</span>BigInt ()](#apidoc.element.seriate.BigInt)
- description and source-code
```javascript
BigInt = function () {
  return {
    type: TYPES.BigInt
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Binary"></a>[function <span class="apidocSignatureSpan">seriate.</span>Binary (length)](#apidoc.element.seriate.Binary)
- description and source-code
```javascript
Binary = function (length) {
  return {
    type: TYPES.Binary,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Bit"></a>[function <span class="apidocSignatureSpan">seriate.</span>Bit ()](#apidoc.element.seriate.Bit)
- description and source-code
```javascript
Bit = function () {
  return {
    type: TYPES.Bit
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.CHAR"></a>[function <span class="apidocSignatureSpan">seriate.</span>CHAR (length)](#apidoc.element.seriate.CHAR)
- description and source-code
```javascript
CHAR = function (length) {
  return {
    type: TYPES.Char,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Char"></a>[function <span class="apidocSignatureSpan">seriate.</span>Char (length)](#apidoc.element.seriate.Char)
- description and source-code
```javascript
Char = function (length) {
  return {
    type: TYPES.Char,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.DATE"></a>[function <span class="apidocSignatureSpan">seriate.</span>DATE ()](#apidoc.element.seriate.DATE)
- description and source-code
```javascript
DATE = function () {
  return {
    type: TYPES.Date
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.DATETIME"></a>[function <span class="apidocSignatureSpan">seriate.</span>DATETIME ()](#apidoc.element.seriate.DATETIME)
- description and source-code
```javascript
DATETIME = function () {
  return {
    type: TYPES.DateTime
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.DATETIME2"></a>[function <span class="apidocSignatureSpan">seriate.</span>DATETIME2 (scale)](#apidoc.element.seriate.DATETIME2)
- description and source-code
```javascript
DATETIME2 = function (scale) {
  return {
    type: TYPES.DateTime2,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.DATETIMEOFFSET"></a>[function <span class="apidocSignatureSpan">seriate.</span>DATETIMEOFFSET (scale)](#apidoc.element.seriate.DATETIMEOFFSET)
- description and source-code
```javascript
DATETIMEOFFSET = function (scale) {
  return {
    type: TYPES.DateTimeOffset,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.DECIMAL"></a>[function <span class="apidocSignatureSpan">seriate.</span>DECIMAL (precision, scale)](#apidoc.element.seriate.DECIMAL)
- description and source-code
```javascript
DECIMAL = function (precision, scale) {
  return {
    type: TYPES.Decimal,
    precision: precision,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Date"></a>[function <span class="apidocSignatureSpan">seriate.</span>Date ()](#apidoc.element.seriate.Date)
- description and source-code
```javascript
Date = function () {
  return {
    type: TYPES.Date
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.DateTime"></a>[function <span class="apidocSignatureSpan">seriate.</span>DateTime ()](#apidoc.element.seriate.DateTime)
- description and source-code
```javascript
DateTime = function () {
  return {
    type: TYPES.DateTime
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.DateTime2"></a>[function <span class="apidocSignatureSpan">seriate.</span>DateTime2 (scale)](#apidoc.element.seriate.DateTime2)
- description and source-code
```javascript
DateTime2 = function (scale) {
  return {
    type: TYPES.DateTime2,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.DateTimeOffset"></a>[function <span class="apidocSignatureSpan">seriate.</span>DateTimeOffset (scale)](#apidoc.element.seriate.DateTimeOffset)
- description and source-code
```javascript
DateTimeOffset = function (scale) {
  return {
    type: TYPES.DateTimeOffset,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Decimal"></a>[function <span class="apidocSignatureSpan">seriate.</span>Decimal (precision, scale)](#apidoc.element.seriate.Decimal)
- description and source-code
```javascript
Decimal = function (precision, scale) {
  return {
    type: TYPES.Decimal,
    precision: precision,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.FLOAT"></a>[function <span class="apidocSignatureSpan">seriate.</span>FLOAT ()](#apidoc.element.seriate.FLOAT)
- description and source-code
```javascript
FLOAT = function () {
  return {
    type: TYPES.Float
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Float"></a>[function <span class="apidocSignatureSpan">seriate.</span>Float ()](#apidoc.element.seriate.Float)
- description and source-code
```javascript
Float = function () {
  return {
    type: TYPES.Float
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.GEOGRAPHY"></a>[function <span class="apidocSignatureSpan">seriate.</span>GEOGRAPHY ()](#apidoc.element.seriate.GEOGRAPHY)
- description and source-code
```javascript
GEOGRAPHY = function () {
  return {
    type: TYPES.Geography
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.GEOMETRY"></a>[function <span class="apidocSignatureSpan">seriate.</span>GEOMETRY ()](#apidoc.element.seriate.GEOMETRY)
- description and source-code
```javascript
GEOMETRY = function () {
  return {
    type: TYPES.Geometry
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Geography"></a>[function <span class="apidocSignatureSpan">seriate.</span>Geography ()](#apidoc.element.seriate.Geography)
- description and source-code
```javascript
Geography = function () {
  return {
    type: TYPES.Geography
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Geometry"></a>[function <span class="apidocSignatureSpan">seriate.</span>Geometry ()](#apidoc.element.seriate.Geometry)
- description and source-code
```javascript
Geometry = function () {
  return {
    type: TYPES.Geometry
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.IMAGE"></a>[function <span class="apidocSignatureSpan">seriate.</span>IMAGE ()](#apidoc.element.seriate.IMAGE)
- description and source-code
```javascript
IMAGE = function () {
  return {
    type: TYPES.Image
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.INT"></a>[function <span class="apidocSignatureSpan">seriate.</span>INT ()](#apidoc.element.seriate.INT)
- description and source-code
```javascript
INT = function () {
  return {
    type: TYPES.Int
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Image"></a>[function <span class="apidocSignatureSpan">seriate.</span>Image ()](#apidoc.element.seriate.Image)
- description and source-code
```javascript
Image = function () {
  return {
    type: TYPES.Image
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Int"></a>[function <span class="apidocSignatureSpan">seriate.</span>Int ()](#apidoc.element.seriate.Int)
- description and source-code
```javascript
Int = function () {
  return {
    type: TYPES.Int
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.MONEY"></a>[function <span class="apidocSignatureSpan">seriate.</span>MONEY ()](#apidoc.element.seriate.MONEY)
- description and source-code
```javascript
MONEY = function () {
  return {
    type: TYPES.Money
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Money"></a>[function <span class="apidocSignatureSpan">seriate.</span>Money ()](#apidoc.element.seriate.Money)
- description and source-code
```javascript
Money = function () {
  return {
    type: TYPES.Money
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.NCHAR"></a>[function <span class="apidocSignatureSpan">seriate.</span>NCHAR (length)](#apidoc.element.seriate.NCHAR)
- description and source-code
```javascript
NCHAR = function (length) {
  return {
    type: TYPES.NChar,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.NChar"></a>[function <span class="apidocSignatureSpan">seriate.</span>NChar (length)](#apidoc.element.seriate.NChar)
- description and source-code
```javascript
NChar = function (length) {
  return {
    type: TYPES.NChar,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.NTEXT"></a>[function <span class="apidocSignatureSpan">seriate.</span>NTEXT ()](#apidoc.element.seriate.NTEXT)
- description and source-code
```javascript
NTEXT = function () {
  return {
    type: TYPES.NText
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.NText"></a>[function <span class="apidocSignatureSpan">seriate.</span>NText ()](#apidoc.element.seriate.NText)
- description and source-code
```javascript
NText = function () {
  return {
    type: TYPES.NText
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.NUMERIC"></a>[function <span class="apidocSignatureSpan">seriate.</span>NUMERIC (precision, scale)](#apidoc.element.seriate.NUMERIC)
- description and source-code
```javascript
NUMERIC = function (precision, scale) {
  return {
    type: TYPES.Numeric,
    precision: precision,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.NVARCHAR"></a>[function <span class="apidocSignatureSpan">seriate.</span>NVARCHAR (length)](#apidoc.element.seriate.NVARCHAR)
- description and source-code
```javascript
NVARCHAR = function (length) {
  return {
    type: TYPES.NVarChar,
    length: length
  };
}
```
- example usage
```shell
...
				{ id: 1, firstName: "James", middleName: "Paul"},
				{ id: 2, firstName: "John", middleName: "Winston" },
				{ id: 3, firstName: "George", middleName: "Harold" },
				{ id: 4, firstName: "Richard", middleName: "Parkin" }
			],
			asTable: {
				id: sql.INT,
				firstName: sql.NVARCHAR(50),
				middleName: sql.NVARCHAR(50)
			}
		}
	}
} )
'''
...
```

#### <a name="apidoc.element.seriate.NVarChar"></a>[function <span class="apidocSignatureSpan">seriate.</span>NVarChar (length)](#apidoc.element.seriate.NVarChar)
- description and source-code
```javascript
NVarChar = function (length) {
  return {
    type: TYPES.NVarChar,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Numeric"></a>[function <span class="apidocSignatureSpan">seriate.</span>Numeric (precision, scale)](#apidoc.element.seriate.Numeric)
- description and source-code
```javascript
Numeric = function (precision, scale) {
  return {
    type: TYPES.Numeric,
    precision: precision,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.REAL"></a>[function <span class="apidocSignatureSpan">seriate.</span>REAL ()](#apidoc.element.seriate.REAL)
- description and source-code
```javascript
REAL = function () {
  return {
    type: TYPES.Real
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Real"></a>[function <span class="apidocSignatureSpan">seriate.</span>Real ()](#apidoc.element.seriate.Real)
- description and source-code
```javascript
Real = function () {
  return {
    type: TYPES.Real
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.SMALLDATETIME"></a>[function <span class="apidocSignatureSpan">seriate.</span>SMALLDATETIME ()](#apidoc.element.seriate.SMALLDATETIME)
- description and source-code
```javascript
SMALLDATETIME = function () {
  return {
    type: TYPES.SmallDateTime
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.SMALLINT"></a>[function <span class="apidocSignatureSpan">seriate.</span>SMALLINT ()](#apidoc.element.seriate.SMALLINT)
- description and source-code
```javascript
SMALLINT = function () {
  return {
    type: TYPES.SmallInt
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.SMALLMONEY"></a>[function <span class="apidocSignatureSpan">seriate.</span>SMALLMONEY ()](#apidoc.element.seriate.SMALLMONEY)
- description and source-code
```javascript
SMALLMONEY = function () {
  return {
    type: TYPES.SmallMoney
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.SmallDateTime"></a>[function <span class="apidocSignatureSpan">seriate.</span>SmallDateTime ()](#apidoc.element.seriate.SmallDateTime)
- description and source-code
```javascript
SmallDateTime = function () {
  return {
    type: TYPES.SmallDateTime
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.SmallInt"></a>[function <span class="apidocSignatureSpan">seriate.</span>SmallInt ()](#apidoc.element.seriate.SmallInt)
- description and source-code
```javascript
SmallInt = function () {
  return {
    type: TYPES.SmallInt
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.SmallMoney"></a>[function <span class="apidocSignatureSpan">seriate.</span>SmallMoney ()](#apidoc.element.seriate.SmallMoney)
- description and source-code
```javascript
SmallMoney = function () {
  return {
    type: TYPES.SmallMoney
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.TEXT"></a>[function <span class="apidocSignatureSpan">seriate.</span>TEXT ()](#apidoc.element.seriate.TEXT)
- description and source-code
```javascript
TEXT = function () {
  return {
    type: TYPES.Text
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.TIME"></a>[function <span class="apidocSignatureSpan">seriate.</span>TIME (scale)](#apidoc.element.seriate.TIME)
- description and source-code
```javascript
TIME = function (scale) {
  return {
    type: TYPES.Time,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.TINYINT"></a>[function <span class="apidocSignatureSpan">seriate.</span>TINYINT ()](#apidoc.element.seriate.TINYINT)
- description and source-code
```javascript
TINYINT = function () {
  return {
    type: TYPES.TinyInt
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.TVP"></a>[function <span class="apidocSignatureSpan">seriate.</span>TVP (tvpType)](#apidoc.element.seriate.TVP)
- description and source-code
```javascript
TVP = function (tvpType) {
  return {
    type: TYPES.TVP,
    tvpType: tvpType
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Text"></a>[function <span class="apidocSignatureSpan">seriate.</span>Text ()](#apidoc.element.seriate.Text)
- description and source-code
```javascript
Text = function () {
  return {
    type: TYPES.Text
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Time"></a>[function <span class="apidocSignatureSpan">seriate.</span>Time (scale)](#apidoc.element.seriate.Time)
- description and source-code
```javascript
Time = function (scale) {
  return {
    type: TYPES.Time,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.TinyInt"></a>[function <span class="apidocSignatureSpan">seriate.</span>TinyInt ()](#apidoc.element.seriate.TinyInt)
- description and source-code
```javascript
TinyInt = function () {
  return {
    type: TYPES.TinyInt
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.UDT"></a>[function <span class="apidocSignatureSpan">seriate.</span>UDT ()](#apidoc.element.seriate.UDT)
- description and source-code
```javascript
UDT = function () {
  return {
    type: TYPES.UDT
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.UNIQUEIDENTIFIER"></a>[function <span class="apidocSignatureSpan">seriate.</span>UNIQUEIDENTIFIER ()](#apidoc.element.seriate.UNIQUEIDENTIFIER)
- description and source-code
```javascript
UNIQUEIDENTIFIER = function () {
  return {
    type: TYPES.UniqueIdentifier
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.UniqueIdentifier"></a>[function <span class="apidocSignatureSpan">seriate.</span>UniqueIdentifier ()](#apidoc.element.seriate.UniqueIdentifier)
- description and source-code
```javascript
UniqueIdentifier = function () {
  return {
    type: TYPES.UniqueIdentifier
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.VARBINARY"></a>[function <span class="apidocSignatureSpan">seriate.</span>VARBINARY (length)](#apidoc.element.seriate.VARBINARY)
- description and source-code
```javascript
VARBINARY = function (length) {
  return {
    type: TYPES.VarBinary,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.VARCHAR"></a>[function <span class="apidocSignatureSpan">seriate.</span>VARCHAR (length)](#apidoc.element.seriate.VARCHAR)
- description and source-code
```javascript
VARCHAR = function (length) {
  return {
    type: TYPES.VarChar,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.VarBinary"></a>[function <span class="apidocSignatureSpan">seriate.</span>VarBinary (length)](#apidoc.element.seriate.VarBinary)
- description and source-code
```javascript
VarBinary = function (length) {
  return {
    type: TYPES.VarBinary,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.VarChar"></a>[function <span class="apidocSignatureSpan">seriate.</span>VarChar (length)](#apidoc.element.seriate.VarChar)
- description and source-code
```javascript
VarChar = function (length) {
  return {
    type: TYPES.VarChar,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.XML"></a>[function <span class="apidocSignatureSpan">seriate.</span>XML ()](#apidoc.element.seriate.XML)
- description and source-code
```javascript
XML = function () {
  return {
    type: TYPES.Xml
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Xml"></a>[function <span class="apidocSignatureSpan">seriate.</span>Xml ()](#apidoc.element.seriate.Xml)
- description and source-code
```javascript
Xml = function () {
  return {
    type: TYPES.Xml
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.addConnection"></a>[function <span class="apidocSignatureSpan">seriate.</span>addConnection ( config )](#apidoc.element.seriate.addConnection)
- description and source-code
```javascript
addConnection = function ( config ) {
		connections.add( config );
	}
```
- example usage
```shell
...

#### Specifying a step using a callback that takes an 'execute' continuation

Here's an example of using a plain context to read a table, and then use data from that read to determine details about the next
 step:

'''javascript
// add a named connection pool
sql.addConnection( {
	name: "example-1",
	user: "username",
	password: "pwd",
	host: "127.0.0.1",
	database: "master"
} );
...
```

#### <a name="apidoc.element.seriate.closeConnection"></a>[function <span class="apidocSignatureSpan">seriate.</span>closeConnection ( config )](#apidoc.element.seriate.closeConnection)
- description and source-code
```javascript
closeConnection = function ( config ) {
		connections.close( config );
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.emit"></a>[function <span class="apidocSignatureSpan">seriate.</span>emit ( topic, data )](#apidoc.element.seriate.emit)
- description and source-code
```javascript
emit = function ( topic, data ) {
		var envelope = this.getEnvelope( topic, data );
		this._cache = this._cache || {};
		var cache = this._cache[ topic ];
		var invoker = function( subDef ) {
			subDef.invokeSubscriber( envelope.data, envelope );
		};
		if ( !cache ) {
			cache = this._cache[ topic ] = [];
			var cacherFn = getCacher( topic, cache, invoker );
			_.each( this._subscriptions, function( candidates ) {
				_.each( slice.call( candidates, 0 ), cacherFn );
			} );
		} else {
			_.each( slice.call( cache, 0 ), invoker );
		}
	}
```
- example usage
```shell
...
		config.host || config.server,
		config.port || 1433,
		config.database,
		config.user );
	pool = state.pools[ name ] = new sql.Connection( config );

	pool.on( "connect", function() {
		api.emit( "connected", { name: name } );
		log.info( "Connected to \"%s\"", name );
	} );

	pool.on( "close", function() {
		api.emit( "closed", { name: name } );
		log.info( "Closed connection to \"%s\"", name );
		pool.removeAllListeners();
...
```

#### <a name="apidoc.element.seriate.execute"></a>[function <span class="apidocSignatureSpan">seriate.</span>execute ( connection, queryOptions )](#apidoc.element.seriate.execute)
- description and source-code
```javascript
execute = function ( connection, queryOptions ) {
		if ( arguments.length === 1 ) {
			queryOptions = connection;
			connection = undefined;
		}
		var conn = connections.get( connection );
		var options = { metrics: this.metrics, namespace: this.metricsNamespace, connection: conn };
		return promisify( new SqlContext( options ), queryOptions )
			.then( function( data ) {
				if ( data.__result__ ) {
					return data.__result__;
				} else {
					return data[ queryOptions.procedure || queryOptions.name ];
				}
			} );
	}
```
- example usage
```shell
...
var connection = {
	user: "username",
	password: "pwd",
	host: "127.0.0.1",
	database: "master"
};

sql.execute( connection, {
		name: "selectFromSomeTableById",
		preparedSql: "select * from someTable where id = @id",
		params: {
			id: {
				val: 123,
				type: sql.INT
			}
...
```

#### <a name="apidoc.element.seriate.executeTransaction"></a>[function <span class="apidocSignatureSpan">seriate.</span>executeTransaction ( connection, queryOptions )](#apidoc.element.seriate.executeTransaction)
- description and source-code
```javascript
executeTransaction = function ( connection, queryOptions ) {
		if ( arguments.length === 1 ) {
			queryOptions = connection;
			connection = undefined;
		}
		var conn = connections.get( connection );
		var options = { metrics: this.metrics, namespace: this.metricsNamespace, connection: conn };
		return promisify( new TransactionContext( options ), queryOptions );
	}
```
- example usage
```shell
...
var connection = {
	user: "username",
	password: "pwd",
	host: "127.0.0.1",
	database: "master"
};

sql.executeTransaction( connection, {
		procedure: "UpdateCustomer",
		params: {
			customerid: {
				val: id,
				type: sql.INT
			},
			balance: {
...
```

#### <a name="apidoc.element.seriate.first"></a>[function <span class="apidocSignatureSpan">seriate.</span>first ()](#apidoc.element.seriate.first)
- description and source-code
```javascript
first = function () {
		var args = Array.prototype.slice.call( arguments, 0 );
		delete args[ args.length - 1 ].stream;
		return this.execute.apply( this, args ).then( function( rows ) {
			return rows[ 0 ];
		} );
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.fromFile"></a>[function <span class="apidocSignatureSpan">seriate.</span>fromFile ( p )](#apidoc.element.seriate.fromFile)
- description and source-code
```javascript
fromFile = function ( p ) {
		p = _getFilePath( p );
		var ext = path.extname( p );
		p = ( ext === "." ) ? ( p + "sql" ) : ( ext.length === 0 ) ? p + ".sql" : p;
		var content = fileCache[ p ];
		if ( _.isEmpty( content ) ) {
			content = fs.readFileSync( p, { encoding: "utf8" } );
			fileCache[ p ] = content;
		}
		return content;
	}
```
- example usage
```shell
...
} );

sql.getPlainContext()
	.step( "readUsers", {
		query: "select * From sys.sysusers"
		// optionally you could do this if the
		// above query were in a readUsers.sql file
		// query: sql.fromFile( "readUsers" );
	} )
	.end( function( sets ){
		// sets has a "readUsers" property
		// which contains the results of the query
	} )
	.error( function( err ){
		console.log( err );
...
```

#### <a name="apidoc.element.seriate.getEnvelope"></a>[function <span class="apidocSignatureSpan">seriate.</span>getEnvelope ( topic, data )](#apidoc.element.seriate.getEnvelope)
- description and source-code
```javascript
getEnvelope = function ( topic, data ) {
		return {
			topic: topic,
			timeStamp: new Date(),
			data: data
		};
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.getPlainContext"></a>[function <span class="apidocSignatureSpan">seriate.</span>getPlainContext ( connection )](#apidoc.element.seriate.getPlainContext)
- description and source-code
```javascript
getPlainContext = function ( connection ) {
		var conn = connections.get( connection );
		var options = { metrics: this.metrics, namespace: this.metricsNamespace, connection: conn };
		return new SqlContext( options );
	}
```
- example usage
```shell
...
sql.setDefault( {
	user: "username",
	password: "pwd",
	host: "127.0.0.1",
	database: "master"
} );

sql.getPlainContext()
	.step( "readUsers", {
		query: "select * From sys.sysusers"
		// optionally you could do this if the
		// above query were in a readUsers.sql file
		// query: sql.fromFile( "readUsers" );
	} )
	.end( function( sets ){
...
```

#### <a name="apidoc.element.seriate.getTransactionContext"></a>[function <span class="apidocSignatureSpan">seriate.</span>getTransactionContext ( connection )](#apidoc.element.seriate.getTransactionContext)
- description and source-code
```javascript
getTransactionContext = function ( connection ) {
		var options = { metrics: this.metrics, namespace: this.metricsNamespace };
		if ( connection && connection.isolationLevel ) {
			options.isolationLevel = connection.isolationLevel;
			delete connection.isolationLevel;
		}
		options.connection = connections.get( connection );
		return new TransactionContext( options );
	}
```
- example usage
```shell
...
sql.addConnection( {
	user: "username",
	password: "pwd",
	host: "127.0.0.1",
	database: "master"
})

sql.getTransactionContext()
	.step( "readUsers", {
		query: "select * From sys.sysusers"
	} )
	.step( "usersTransforms", function( execute, data ) {
		// data will contain a 'readUsers' property with
		// the prior step's results in an array. You can
		// use this approach with a callback to dynamically
...
```

#### <a name="apidoc.element.seriate.off"></a>[function <span class="apidocSignatureSpan">seriate.</span>off ( topic, context )](#apidoc.element.seriate.off)
- description and source-code
```javascript
off = function ( topic, context ) {
		var self = this;
		self._subscriptions = self._subscriptions || {};
		self._cache = self._cache || {};
		switch ( arguments.length ) {
			case 0:
				_.each( self._subscriptions, function( tpc ) {
					_.each( tpc, function( subDef, idx ) {
						removeSubscriber( subDef, self, idx, tpc );
					} );
				} );
				self._subscriptions = {};
				break;
			case 1:
				var type = Object.prototype.toString.call( topic ) === "[object String]" ? "topic" : topic instanceof SubscriptionDefinition
 ? "def" : "context";
				switch ( type ) {
					case "topic":
						if ( self._subscriptions[ topic ] ) {
							_.each( self._subscriptions[ topic ], function( subDef, idx ) {
								removeSubscriber( subDef, self, idx, self._subscriptions[ topic ] );
							} );
						}
						break;
					case "context":
						_.each( self._subscriptions, function( subs ) {
							_.each( _.clone( subs ), function( subDef, idx ) {
								if ( subDef._context === topic ) {
									removeSubscriber( subDef, self, idx, subs );
								}
							} );
						} );
						break;
					default:
						// topic arg is the subDef in this case....
						_.each( self._subscriptions[ topic.topic ], function( subDef, idx ) {
							if ( subDef === topic ) {
								removeSubscriber( subDef, self, idx, self._subscriptions[ topic.topic ] );
							}
						} );
						break;
				}
				break;
			default:
				_.each( _.clone( self._subscriptions[ topic ] ), function( subDef, idx ) {
					if ( subDef._context === context ) {
						removeSubscriber( subDef, self, idx, self._subscriptions[ topic ] );
					}
				} );
				break;
		}
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.on"></a>[function <span class="apidocSignatureSpan">seriate.</span>on ( topic, callback )](#apidoc.element.seriate.on)
- description and source-code
```javascript
on = function ( topic, callback ) {
		var self = this;
		self._subscriptions = self._subscriptions || {};
		self._subscriptions[ topic ] = self._subscriptions[ topic ] || [];
		var subDef = new SubscriptionDefinition( topic, callback, self );
		self._subscriptions[ topic ].push( subDef );

		// Next, add the SubscriptionDefinition to any relevant existing cache(s)
		_.each( self._cache, function( list, key ) {
			getCacher( key, list )( subDef );
		} );

		return self._subscriptions[ topic ][ self._subscriptions[ topic ].length - 1 ];
	}
```
- example usage
```shell
...
		name,
		config.host || config.server,
		config.port || 1433,
		config.database,
		config.user );
	pool = state.pools[ name ] = new sql.Connection( config );

	pool.on( "connect", function() {
		api.emit( "connected", { name: name } );
		log.info( "Connected to \"%s\"", name );
	} );

	pool.on( "close", function() {
		api.emit( "closed", { name: name } );
		log.info( "Closed connection to \"%s\"", name );
...
```

#### <a name="apidoc.element.seriate.once"></a>[function <span class="apidocSignatureSpan">seriate.</span>once ( topic, callback )](#apidoc.element.seriate.once)
- description and source-code
```javascript
once = function ( topic, callback ) {
		return this.on( topic, callback ).once();
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.resetConnections"></a>[function <span class="apidocSignatureSpan">seriate.</span>resetConnections ()](#apidoc.element.seriate.resetConnections)
- description and source-code
```javascript
resetConnections = function () {
		connections.reset();
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.setDefault"></a>[function <span class="apidocSignatureSpan">seriate.</span>setDefault ( config )](#apidoc.element.seriate.setDefault)
- description and source-code
```javascript
setDefault = function ( config ) {
		config.name = "default";
		connections.add( config );
	}
```
- example usage
```shell
...

#### Specifying a step using just the query options object argument

Here's an example of using a plain context to read a table:

'''javascript
// set a default connection pool
sql.setDefault( {
	user: "username",
	password: "pwd",
	host: "127.0.0.1",
	database: "master"
} );

sql.getPlainContext()
...
```

#### <a name="apidoc.element.seriate.setDefaultConfig"></a>[function <span class="apidocSignatureSpan">seriate.</span>setDefaultConfig ( config )](#apidoc.element.seriate.setDefaultConfig)
- description and source-code
```javascript
setDefaultConfig = function ( config ) {
		config.name = "default";
		connections.add( config );
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.useMetrics"></a>[function <span class="apidocSignatureSpan">seriate.</span>useMetrics ( metrics, namespace )](#apidoc.element.seriate.useMetrics)
- description and source-code
```javascript
useMetrics = function ( metrics, namespace ) {
		this.metrics = metrics;
		this.metricsNamespace = namespace;
	}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.BigInt"></a>[module seriate.BigInt](#apidoc.module.seriate.BigInt)

#### <a name="apidoc.element.seriate.BigInt.BigInt"></a>[function <span class="apidocSignatureSpan">seriate.</span>BigInt ()](#apidoc.element.seriate.BigInt.BigInt)
- description and source-code
```javascript
BigInt = function () {
  return {
    type: TYPES.BigInt
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.BigInt.inspect"></a>[function <span class="apidocSignatureSpan">seriate.BigInt.</span>inspect ()](#apidoc.element.seriate.BigInt.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Binary"></a>[module seriate.Binary](#apidoc.module.seriate.Binary)

#### <a name="apidoc.element.seriate.Binary.Binary"></a>[function <span class="apidocSignatureSpan">seriate.</span>Binary (length)](#apidoc.element.seriate.Binary.Binary)
- description and source-code
```javascript
Binary = function (length) {
  return {
    type: TYPES.Binary,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Binary.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Binary.</span>inspect ()](#apidoc.element.seriate.Binary.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Bit"></a>[module seriate.Bit](#apidoc.module.seriate.Bit)

#### <a name="apidoc.element.seriate.Bit.Bit"></a>[function <span class="apidocSignatureSpan">seriate.</span>Bit ()](#apidoc.element.seriate.Bit.Bit)
- description and source-code
```javascript
Bit = function () {
  return {
    type: TYPES.Bit
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Bit.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Bit.</span>inspect ()](#apidoc.element.seriate.Bit.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Char"></a>[module seriate.Char](#apidoc.module.seriate.Char)

#### <a name="apidoc.element.seriate.Char.Char"></a>[function <span class="apidocSignatureSpan">seriate.</span>Char (length)](#apidoc.element.seriate.Char.Char)
- description and source-code
```javascript
Char = function (length) {
  return {
    type: TYPES.Char,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Char.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Char.</span>inspect ()](#apidoc.element.seriate.Char.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Date"></a>[module seriate.Date](#apidoc.module.seriate.Date)

#### <a name="apidoc.element.seriate.Date.Date"></a>[function <span class="apidocSignatureSpan">seriate.</span>Date ()](#apidoc.element.seriate.Date.Date)
- description and source-code
```javascript
Date = function () {
  return {
    type: TYPES.Date
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Date.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Date.</span>inspect ()](#apidoc.element.seriate.Date.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.DateTime"></a>[module seriate.DateTime](#apidoc.module.seriate.DateTime)

#### <a name="apidoc.element.seriate.DateTime.DateTime"></a>[function <span class="apidocSignatureSpan">seriate.</span>DateTime ()](#apidoc.element.seriate.DateTime.DateTime)
- description and source-code
```javascript
DateTime = function () {
  return {
    type: TYPES.DateTime
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.DateTime.inspect"></a>[function <span class="apidocSignatureSpan">seriate.DateTime.</span>inspect ()](#apidoc.element.seriate.DateTime.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.DateTime2"></a>[module seriate.DateTime2](#apidoc.module.seriate.DateTime2)

#### <a name="apidoc.element.seriate.DateTime2.DateTime2"></a>[function <span class="apidocSignatureSpan">seriate.</span>DateTime2 (scale)](#apidoc.element.seriate.DateTime2.DateTime2)
- description and source-code
```javascript
DateTime2 = function (scale) {
  return {
    type: TYPES.DateTime2,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.DateTime2.inspect"></a>[function <span class="apidocSignatureSpan">seriate.DateTime2.</span>inspect ()](#apidoc.element.seriate.DateTime2.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.DateTimeOffset"></a>[module seriate.DateTimeOffset](#apidoc.module.seriate.DateTimeOffset)

#### <a name="apidoc.element.seriate.DateTimeOffset.DateTimeOffset"></a>[function <span class="apidocSignatureSpan">seriate.</span>DateTimeOffset (scale)](#apidoc.element.seriate.DateTimeOffset.DateTimeOffset)
- description and source-code
```javascript
DateTimeOffset = function (scale) {
  return {
    type: TYPES.DateTimeOffset,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.DateTimeOffset.inspect"></a>[function <span class="apidocSignatureSpan">seriate.DateTimeOffset.</span>inspect ()](#apidoc.element.seriate.DateTimeOffset.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Decimal"></a>[module seriate.Decimal](#apidoc.module.seriate.Decimal)

#### <a name="apidoc.element.seriate.Decimal.Decimal"></a>[function <span class="apidocSignatureSpan">seriate.</span>Decimal (precision, scale)](#apidoc.element.seriate.Decimal.Decimal)
- description and source-code
```javascript
Decimal = function (precision, scale) {
  return {
    type: TYPES.Decimal,
    precision: precision,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Decimal.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Decimal.</span>inspect ()](#apidoc.element.seriate.Decimal.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Float"></a>[module seriate.Float](#apidoc.module.seriate.Float)

#### <a name="apidoc.element.seriate.Float.Float"></a>[function <span class="apidocSignatureSpan">seriate.</span>Float ()](#apidoc.element.seriate.Float.Float)
- description and source-code
```javascript
Float = function () {
  return {
    type: TYPES.Float
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Float.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Float.</span>inspect ()](#apidoc.element.seriate.Float.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Geography"></a>[module seriate.Geography](#apidoc.module.seriate.Geography)

#### <a name="apidoc.element.seriate.Geography.Geography"></a>[function <span class="apidocSignatureSpan">seriate.</span>Geography ()](#apidoc.element.seriate.Geography.Geography)
- description and source-code
```javascript
Geography = function () {
  return {
    type: TYPES.Geography
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Geography.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Geography.</span>inspect ()](#apidoc.element.seriate.Geography.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Geometry"></a>[module seriate.Geometry](#apidoc.module.seriate.Geometry)

#### <a name="apidoc.element.seriate.Geometry.Geometry"></a>[function <span class="apidocSignatureSpan">seriate.</span>Geometry ()](#apidoc.element.seriate.Geometry.Geometry)
- description and source-code
```javascript
Geometry = function () {
  return {
    type: TYPES.Geometry
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Geometry.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Geometry.</span>inspect ()](#apidoc.element.seriate.Geometry.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Image"></a>[module seriate.Image](#apidoc.module.seriate.Image)

#### <a name="apidoc.element.seriate.Image.Image"></a>[function <span class="apidocSignatureSpan">seriate.</span>Image ()](#apidoc.element.seriate.Image.Image)
- description and source-code
```javascript
Image = function () {
  return {
    type: TYPES.Image
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Image.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Image.</span>inspect ()](#apidoc.element.seriate.Image.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Int"></a>[module seriate.Int](#apidoc.module.seriate.Int)

#### <a name="apidoc.element.seriate.Int.Int"></a>[function <span class="apidocSignatureSpan">seriate.</span>Int ()](#apidoc.element.seriate.Int.Int)
- description and source-code
```javascript
Int = function () {
  return {
    type: TYPES.Int
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Int.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Int.</span>inspect ()](#apidoc.element.seriate.Int.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Money"></a>[module seriate.Money](#apidoc.module.seriate.Money)

#### <a name="apidoc.element.seriate.Money.Money"></a>[function <span class="apidocSignatureSpan">seriate.</span>Money ()](#apidoc.element.seriate.Money.Money)
- description and source-code
```javascript
Money = function () {
  return {
    type: TYPES.Money
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Money.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Money.</span>inspect ()](#apidoc.element.seriate.Money.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.NChar"></a>[module seriate.NChar](#apidoc.module.seriate.NChar)

#### <a name="apidoc.element.seriate.NChar.NChar"></a>[function <span class="apidocSignatureSpan">seriate.</span>NChar (length)](#apidoc.element.seriate.NChar.NChar)
- description and source-code
```javascript
NChar = function (length) {
  return {
    type: TYPES.NChar,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.NChar.inspect"></a>[function <span class="apidocSignatureSpan">seriate.NChar.</span>inspect ()](#apidoc.element.seriate.NChar.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.NText"></a>[module seriate.NText](#apidoc.module.seriate.NText)

#### <a name="apidoc.element.seriate.NText.NText"></a>[function <span class="apidocSignatureSpan">seriate.</span>NText ()](#apidoc.element.seriate.NText.NText)
- description and source-code
```javascript
NText = function () {
  return {
    type: TYPES.NText
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.NText.inspect"></a>[function <span class="apidocSignatureSpan">seriate.NText.</span>inspect ()](#apidoc.element.seriate.NText.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.NVarChar"></a>[module seriate.NVarChar](#apidoc.module.seriate.NVarChar)

#### <a name="apidoc.element.seriate.NVarChar.NVarChar"></a>[function <span class="apidocSignatureSpan">seriate.</span>NVarChar (length)](#apidoc.element.seriate.NVarChar.NVarChar)
- description and source-code
```javascript
NVarChar = function (length) {
  return {
    type: TYPES.NVarChar,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.NVarChar.inspect"></a>[function <span class="apidocSignatureSpan">seriate.NVarChar.</span>inspect ()](#apidoc.element.seriate.NVarChar.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Numeric"></a>[module seriate.Numeric](#apidoc.module.seriate.Numeric)

#### <a name="apidoc.element.seriate.Numeric.Numeric"></a>[function <span class="apidocSignatureSpan">seriate.</span>Numeric (precision, scale)](#apidoc.element.seriate.Numeric.Numeric)
- description and source-code
```javascript
Numeric = function (precision, scale) {
  return {
    type: TYPES.Numeric,
    precision: precision,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Numeric.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Numeric.</span>inspect ()](#apidoc.element.seriate.Numeric.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Real"></a>[module seriate.Real](#apidoc.module.seriate.Real)

#### <a name="apidoc.element.seriate.Real.Real"></a>[function <span class="apidocSignatureSpan">seriate.</span>Real ()](#apidoc.element.seriate.Real.Real)
- description and source-code
```javascript
Real = function () {
  return {
    type: TYPES.Real
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Real.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Real.</span>inspect ()](#apidoc.element.seriate.Real.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.SmallDateTime"></a>[module seriate.SmallDateTime](#apidoc.module.seriate.SmallDateTime)

#### <a name="apidoc.element.seriate.SmallDateTime.SmallDateTime"></a>[function <span class="apidocSignatureSpan">seriate.</span>SmallDateTime ()](#apidoc.element.seriate.SmallDateTime.SmallDateTime)
- description and source-code
```javascript
SmallDateTime = function () {
  return {
    type: TYPES.SmallDateTime
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.SmallDateTime.inspect"></a>[function <span class="apidocSignatureSpan">seriate.SmallDateTime.</span>inspect ()](#apidoc.element.seriate.SmallDateTime.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.SmallInt"></a>[module seriate.SmallInt](#apidoc.module.seriate.SmallInt)

#### <a name="apidoc.element.seriate.SmallInt.SmallInt"></a>[function <span class="apidocSignatureSpan">seriate.</span>SmallInt ()](#apidoc.element.seriate.SmallInt.SmallInt)
- description and source-code
```javascript
SmallInt = function () {
  return {
    type: TYPES.SmallInt
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.SmallInt.inspect"></a>[function <span class="apidocSignatureSpan">seriate.SmallInt.</span>inspect ()](#apidoc.element.seriate.SmallInt.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.SmallMoney"></a>[module seriate.SmallMoney](#apidoc.module.seriate.SmallMoney)

#### <a name="apidoc.element.seriate.SmallMoney.SmallMoney"></a>[function <span class="apidocSignatureSpan">seriate.</span>SmallMoney ()](#apidoc.element.seriate.SmallMoney.SmallMoney)
- description and source-code
```javascript
SmallMoney = function () {
  return {
    type: TYPES.SmallMoney
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.SmallMoney.inspect"></a>[function <span class="apidocSignatureSpan">seriate.SmallMoney.</span>inspect ()](#apidoc.element.seriate.SmallMoney.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.TVP"></a>[module seriate.TVP](#apidoc.module.seriate.TVP)

#### <a name="apidoc.element.seriate.TVP.TVP"></a>[function <span class="apidocSignatureSpan">seriate.</span>TVP (tvpType)](#apidoc.element.seriate.TVP.TVP)
- description and source-code
```javascript
TVP = function (tvpType) {
  return {
    type: TYPES.TVP,
    tvpType: tvpType
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.TVP.inspect"></a>[function <span class="apidocSignatureSpan">seriate.TVP.</span>inspect ()](#apidoc.element.seriate.TVP.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Text"></a>[module seriate.Text](#apidoc.module.seriate.Text)

#### <a name="apidoc.element.seriate.Text.Text"></a>[function <span class="apidocSignatureSpan">seriate.</span>Text ()](#apidoc.element.seriate.Text.Text)
- description and source-code
```javascript
Text = function () {
  return {
    type: TYPES.Text
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Text.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Text.</span>inspect ()](#apidoc.element.seriate.Text.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Time"></a>[module seriate.Time](#apidoc.module.seriate.Time)

#### <a name="apidoc.element.seriate.Time.Time"></a>[function <span class="apidocSignatureSpan">seriate.</span>Time (scale)](#apidoc.element.seriate.Time.Time)
- description and source-code
```javascript
Time = function (scale) {
  return {
    type: TYPES.Time,
    scale: scale
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Time.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Time.</span>inspect ()](#apidoc.element.seriate.Time.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.TinyInt"></a>[module seriate.TinyInt](#apidoc.module.seriate.TinyInt)

#### <a name="apidoc.element.seriate.TinyInt.TinyInt"></a>[function <span class="apidocSignatureSpan">seriate.</span>TinyInt ()](#apidoc.element.seriate.TinyInt.TinyInt)
- description and source-code
```javascript
TinyInt = function () {
  return {
    type: TYPES.TinyInt
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.TinyInt.inspect"></a>[function <span class="apidocSignatureSpan">seriate.TinyInt.</span>inspect ()](#apidoc.element.seriate.TinyInt.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.UDT"></a>[module seriate.UDT](#apidoc.module.seriate.UDT)

#### <a name="apidoc.element.seriate.UDT.UDT"></a>[function <span class="apidocSignatureSpan">seriate.</span>UDT ()](#apidoc.element.seriate.UDT.UDT)
- description and source-code
```javascript
UDT = function () {
  return {
    type: TYPES.UDT
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.UDT.inspect"></a>[function <span class="apidocSignatureSpan">seriate.UDT.</span>inspect ()](#apidoc.element.seriate.UDT.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.UniqueIdentifier"></a>[module seriate.UniqueIdentifier](#apidoc.module.seriate.UniqueIdentifier)

#### <a name="apidoc.element.seriate.UniqueIdentifier.UniqueIdentifier"></a>[function <span class="apidocSignatureSpan">seriate.</span>UniqueIdentifier ()](#apidoc.element.seriate.UniqueIdentifier.UniqueIdentifier)
- description and source-code
```javascript
UniqueIdentifier = function () {
  return {
    type: TYPES.UniqueIdentifier
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.UniqueIdentifier.inspect"></a>[function <span class="apidocSignatureSpan">seriate.UniqueIdentifier.</span>inspect ()](#apidoc.element.seriate.UniqueIdentifier.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.VarBinary"></a>[module seriate.VarBinary](#apidoc.module.seriate.VarBinary)

#### <a name="apidoc.element.seriate.VarBinary.VarBinary"></a>[function <span class="apidocSignatureSpan">seriate.</span>VarBinary (length)](#apidoc.element.seriate.VarBinary.VarBinary)
- description and source-code
```javascript
VarBinary = function (length) {
  return {
    type: TYPES.VarBinary,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.VarBinary.inspect"></a>[function <span class="apidocSignatureSpan">seriate.VarBinary.</span>inspect ()](#apidoc.element.seriate.VarBinary.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.VarChar"></a>[module seriate.VarChar](#apidoc.module.seriate.VarChar)

#### <a name="apidoc.element.seriate.VarChar.VarChar"></a>[function <span class="apidocSignatureSpan">seriate.</span>VarChar (length)](#apidoc.element.seriate.VarChar.VarChar)
- description and source-code
```javascript
VarChar = function (length) {
  return {
    type: TYPES.VarChar,
    length: length
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.VarChar.inspect"></a>[function <span class="apidocSignatureSpan">seriate.VarChar.</span>inspect ()](#apidoc.element.seriate.VarChar.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.Xml"></a>[module seriate.Xml](#apidoc.module.seriate.Xml)

#### <a name="apidoc.element.seriate.Xml.Xml"></a>[function <span class="apidocSignatureSpan">seriate.</span>Xml ()](#apidoc.element.seriate.Xml.Xml)
- description and source-code
```javascript
Xml = function () {
  return {
    type: TYPES.Xml
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.Xml.inspect"></a>[function <span class="apidocSignatureSpan">seriate.Xml.</span>inspect ()](#apidoc.element.seriate.Xml.inspect)
- description and source-code
```javascript
inspect = function () {
  return "[sql." + key + "]";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.connections"></a>[module seriate.connections](#apidoc.module.seriate.connections)

#### <a name="apidoc.element.seriate.connections.add"></a>[function <span class="apidocSignatureSpan">seriate.connections.</span>add ( config )](#apidoc.element.seriate.connections.add)
- description and source-code
```javascript
function addConnection( config ) {
	var name = getName( config );
	var original = getConfiguration( name );
	var alias = getAlias( config );
	if ( alias !== name && !state.aliases[ alias ] ) {
		state.aliases[ alias ] = name;
	}
	if ( config.host ) {
		config.server = config.host;
	}
	if ( name === "default" || !original ) {
		state.configurations[ name ] = config;
		return connect( name, config );
	} else if ( alias === getAlias( original ) ) {
		return getConnection( config );
	}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.connections.close"></a>[function <span class="apidocSignatureSpan">seriate.connections.</span>close ( config )](#apidoc.element.seriate.connections.close)
- description and source-code
```javascript
function closeConnection( config ) {
	var name = getName( config );
	var pool = state.pools[ name ];

	if ( pool ) {
		pool.close();
	}
}
```
- example usage
```shell
...
}

function closeConnection( config ) {
	var name = getName( config );
	var pool = state.pools[ name ];

	if ( pool ) {
		pool.close();
	}
}

function connect( name, config ) {
	var pool = getPool( name );
	if ( pool ) {
		log.warn( "Connection for \"%s\" that already exists - existing connection pool will be used.", name );
...
```

#### <a name="apidoc.element.seriate.connections.emit"></a>[function <span class="apidocSignatureSpan">seriate.connections.</span>emit ( topic, data )](#apidoc.element.seriate.connections.emit)
- description and source-code
```javascript
emit = function ( topic, data ) {
		var envelope = this.getEnvelope( topic, data );
		this._cache = this._cache || {};
		var cache = this._cache[ topic ];
		var invoker = function( subDef ) {
			subDef.invokeSubscriber( envelope.data, envelope );
		};
		if ( !cache ) {
			cache = this._cache[ topic ] = [];
			var cacherFn = getCacher( topic, cache, invoker );
			_.each( this._subscriptions, function( candidates ) {
				_.each( slice.call( candidates, 0 ), cacherFn );
			} );
		} else {
			_.each( slice.call( cache, 0 ), invoker );
		}
	}
```
- example usage
```shell
...
		config.host || config.server,
		config.port || 1433,
		config.database,
		config.user );
	pool = state.pools[ name ] = new sql.Connection( config );

	pool.on( "connect", function() {
		api.emit( "connected", { name: name } );
		log.info( "Connected to \"%s\"", name );
	} );

	pool.on( "close", function() {
		api.emit( "closed", { name: name } );
		log.info( "Closed connection to \"%s\"", name );
		pool.removeAllListeners();
...
```

#### <a name="apidoc.element.seriate.connections.get"></a>[function <span class="apidocSignatureSpan">seriate.connections.</span>get ( config )](#apidoc.element.seriate.connections.get)
- description and source-code
```javascript
function getConnection( config ) {
	var name = getName( config );
	var pool = state.pools[ name ];
	var connection = state.connections[ name ];
	var configuration = state.configurations[ name ];
	var aliasedName = state.aliases[ name ];
	if ( !pool && !connection && aliasedName ) {
		name = aliasedName;
		pool = state.pools[ name ];
		connection = state.connections[ name ];
		configuration = state.configurations[ name ];
	}

	if ( connection ) {
		return connection;
	} else if ( pool ) {
		connection = pool.connect()
			.then( function() {
				return pool;
			} );
		state.connections[ name ] = connection;
		return connection;
	} else if ( configuration ) {
		return connect( name, configuration );
	} else if ( config === undefined || _.isString( config ) ) {
		return when.reject( new Error( "No connection named \"" + name + "\" exists" ) );
	} else {
		return addConnection( config );
	}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.connections.getEnvelope"></a>[function <span class="apidocSignatureSpan">seriate.connections.</span>getEnvelope ( topic, data )](#apidoc.element.seriate.connections.getEnvelope)
- description and source-code
```javascript
getEnvelope = function ( topic, data ) {
		return {
			topic: topic,
			timeStamp: new Date(),
			data: data
		};
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.connections.off"></a>[function <span class="apidocSignatureSpan">seriate.connections.</span>off ( topic, context )](#apidoc.element.seriate.connections.off)
- description and source-code
```javascript
off = function ( topic, context ) {
		var self = this;
		self._subscriptions = self._subscriptions || {};
		self._cache = self._cache || {};
		switch ( arguments.length ) {
			case 0:
				_.each( self._subscriptions, function( tpc ) {
					_.each( tpc, function( subDef, idx ) {
						removeSubscriber( subDef, self, idx, tpc );
					} );
				} );
				self._subscriptions = {};
				break;
			case 1:
				var type = Object.prototype.toString.call( topic ) === "[object String]" ? "topic" : topic instanceof SubscriptionDefinition
 ? "def" : "context";
				switch ( type ) {
					case "topic":
						if ( self._subscriptions[ topic ] ) {
							_.each( self._subscriptions[ topic ], function( subDef, idx ) {
								removeSubscriber( subDef, self, idx, self._subscriptions[ topic ] );
							} );
						}
						break;
					case "context":
						_.each( self._subscriptions, function( subs ) {
							_.each( _.clone( subs ), function( subDef, idx ) {
								if ( subDef._context === topic ) {
									removeSubscriber( subDef, self, idx, subs );
								}
							} );
						} );
						break;
					default:
						// topic arg is the subDef in this case....
						_.each( self._subscriptions[ topic.topic ], function( subDef, idx ) {
							if ( subDef === topic ) {
								removeSubscriber( subDef, self, idx, self._subscriptions[ topic.topic ] );
							}
						} );
						break;
				}
				break;
			default:
				_.each( _.clone( self._subscriptions[ topic ] ), function( subDef, idx ) {
					if ( subDef._context === context ) {
						removeSubscriber( subDef, self, idx, self._subscriptions[ topic ] );
					}
				} );
				break;
		}
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.connections.on"></a>[function <span class="apidocSignatureSpan">seriate.connections.</span>on ( topic, callback )](#apidoc.element.seriate.connections.on)
- description and source-code
```javascript
on = function ( topic, callback ) {
		var self = this;
		self._subscriptions = self._subscriptions || {};
		self._subscriptions[ topic ] = self._subscriptions[ topic ] || [];
		var subDef = new SubscriptionDefinition( topic, callback, self );
		self._subscriptions[ topic ].push( subDef );

		// Next, add the SubscriptionDefinition to any relevant existing cache(s)
		_.each( self._cache, function( list, key ) {
			getCacher( key, list )( subDef );
		} );

		return self._subscriptions[ topic ][ self._subscriptions[ topic ].length - 1 ];
	}
```
- example usage
```shell
...
		name,
		config.host || config.server,
		config.port || 1433,
		config.database,
		config.user );
	pool = state.pools[ name ] = new sql.Connection( config );

	pool.on( "connect", function() {
		api.emit( "connected", { name: name } );
		log.info( "Connected to \"%s\"", name );
	} );

	pool.on( "close", function() {
		api.emit( "closed", { name: name } );
		log.info( "Closed connection to \"%s\"", name );
...
```

#### <a name="apidoc.element.seriate.connections.once"></a>[function <span class="apidocSignatureSpan">seriate.connections.</span>once ( topic, callback )](#apidoc.element.seriate.connections.once)
- description and source-code
```javascript
once = function ( topic, callback ) {
		return this.on( topic, callback ).once();
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seriate.connections.reset"></a>[function <span class="apidocSignatureSpan">seriate.connections.</span>reset ()](#apidoc.element.seriate.connections.reset)
- description and source-code
```javascript
function resetState() {
	state = {
		pools: {},
		connections: {},
		configurations: {},
		aliases: {}
	};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seriate.utils"></a>[module seriate.utils](#apidoc.module.seriate.utils)

#### <a name="apidoc.element.seriate.utils.fromFile"></a>[function <span class="apidocSignatureSpan">seriate.utils.</span>fromFile ( p )](#apidoc.element.seriate.utils.fromFile)
- description and source-code
```javascript
fromFile = function ( p ) {
		p = _getFilePath( p );
		var ext = path.extname( p );
		p = ( ext === "." ) ? ( p + "sql" ) : ( ext.length === 0 ) ? p + ".sql" : p;
		var content = fileCache[ p ];
		if ( _.isEmpty( content ) ) {
			content = fs.readFileSync( p, { encoding: "utf8" } );
			fileCache[ p ] = content;
		}
		return content;
	}
```
- example usage
```shell
...
} );

sql.getPlainContext()
	.step( "readUsers", {
		query: "select * From sys.sysusers"
		// optionally you could do this if the
		// above query were in a readUsers.sql file
		// query: sql.fromFile( "readUsers" );
	} )
	.end( function( sets ){
		// sets has a "readUsers" property
		// which contains the results of the query
	} )
	.error( function( err ){
		console.log( err );
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

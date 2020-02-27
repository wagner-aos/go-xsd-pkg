# go_Xlink
--
    import "github.com/wagner-aos/go-xsd-pkg/docbook.org/xml/5.0/xsd/xlink.xsd_go"

	Auto-generated by the "go-xsd" package located at:
		github.com/wagner-aos/go-xsd
	Comments on types and fields (if any) are from the XSD file located at:
		docbook.org/xml/5.0/xsd/xlink.xsd

## Usage

#### type TxsdActuate

```go
type TxsdActuate xsdt.Token
```


#### func (TxsdActuate) IsNone

```go
func (me TxsdActuate) IsNone() bool
```
Returns true if the value of this enumerated TxsdActuate is "none".

#### func (TxsdActuate) IsOnLoad

```go
func (me TxsdActuate) IsOnLoad() bool
```
Returns true if the value of this enumerated TxsdActuate is "onLoad".

#### func (TxsdActuate) IsOnRequest

```go
func (me TxsdActuate) IsOnRequest() bool
```
Returns true if the value of this enumerated TxsdActuate is "onRequest".

#### func (TxsdActuate) IsOther

```go
func (me TxsdActuate) IsOther() bool
```
Returns true if the value of this enumerated TxsdActuate is "other".

#### func (*TxsdActuate) Set

```go
func (me *TxsdActuate) Set(s string)
```
Since TxsdActuate is just a simple String type, this merely sets the current
value from the specified string.

#### func (TxsdActuate) String

```go
func (me TxsdActuate) String() string
```
Since TxsdActuate is just a simple String type, this merely returns the current
string value.

#### func (TxsdActuate) ToXsdtToken

```go
func (me TxsdActuate) ToXsdtToken() xsdt.Token
```
This convenience method just performs a simple type conversion to TxsdActuate's
alias type xsdt.Token.

#### type TxsdShow

```go
type TxsdShow xsdt.Token
```


#### func (TxsdShow) IsEmbed

```go
func (me TxsdShow) IsEmbed() bool
```
Returns true if the value of this enumerated TxsdShow is "embed".

#### func (TxsdShow) IsNew

```go
func (me TxsdShow) IsNew() bool
```
Returns true if the value of this enumerated TxsdShow is "new".

#### func (TxsdShow) IsNone

```go
func (me TxsdShow) IsNone() bool
```
Returns true if the value of this enumerated TxsdShow is "none".

#### func (TxsdShow) IsOther

```go
func (me TxsdShow) IsOther() bool
```
Returns true if the value of this enumerated TxsdShow is "other".

#### func (TxsdShow) IsReplace

```go
func (me TxsdShow) IsReplace() bool
```
Returns true if the value of this enumerated TxsdShow is "replace".

#### func (*TxsdShow) Set

```go
func (me *TxsdShow) Set(s string)
```
Since TxsdShow is just a simple String type, this merely sets the current value
from the specified string.

#### func (TxsdShow) String

```go
func (me TxsdShow) String() string
```
Since TxsdShow is just a simple String type, this merely returns the current
string value.

#### func (TxsdShow) ToXsdtToken

```go
func (me TxsdShow) ToXsdtToken() xsdt.Token
```
This convenience method just performs a simple type conversion to TxsdShow's
alias type xsdt.Token.

#### type XsdGoPkgHasAttr_Actuate

```go
type XsdGoPkgHasAttr_Actuate struct {
	Actuate TxsdActuate `xml:"http://www.w3.org/1999/xlink actuate,attr"`
}
```


#### type XsdGoPkgHasAttr_Arcrole

```go
type XsdGoPkgHasAttr_Arcrole struct {
	Arcrole xsdt.String `xml:"http://www.w3.org/1999/xlink arcrole,attr"`
}
```


#### type XsdGoPkgHasAttr_From

```go
type XsdGoPkgHasAttr_From struct {
	From xsdt.Nmtoken `xml:"http://www.w3.org/1999/xlink from,attr"`
}
```


#### type XsdGoPkgHasAttr_Href

```go
type XsdGoPkgHasAttr_Href struct {
	Href xsdt.String `xml:"http://www.w3.org/1999/xlink href,attr"`
}
```


#### type XsdGoPkgHasAttr_Label

```go
type XsdGoPkgHasAttr_Label struct {
	Label xsdt.Nmtoken `xml:"http://www.w3.org/1999/xlink label,attr"`
}
```


#### type XsdGoPkgHasAttr_Role

```go
type XsdGoPkgHasAttr_Role struct {
	Role xsdt.String `xml:"http://www.w3.org/1999/xlink role,attr"`
}
```


#### type XsdGoPkgHasAttr_Show

```go
type XsdGoPkgHasAttr_Show struct {
	Show TxsdShow `xml:"http://www.w3.org/1999/xlink show,attr"`
}
```


#### type XsdGoPkgHasAttr_Title

```go
type XsdGoPkgHasAttr_Title struct {
	Title xsdt.String `xml:"http://www.w3.org/1999/xlink title,attr"`
}
```


#### type XsdGoPkgHasAttr_To

```go
type XsdGoPkgHasAttr_To struct {
	To xsdt.Nmtoken `xml:"http://www.w3.org/1999/xlink to,attr"`
}
```


#### type XsdGoPkgHasAttr_Type

```go
type XsdGoPkgHasAttr_Type struct {
	Type xsdt.String `xml:"http://www.w3.org/1999/xlink type,attr"`
}
```

--
**godocdown** http://github.com/robertkrimen/godocdown
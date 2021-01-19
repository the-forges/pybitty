# PyBitty

[![Build Status](https://travis-ci.org/the-forges/pybitty.svg?branch=main)](https://travis-ci.org/the-forges/pybitty) [![codecov](https://codecov.io/gh/the-forges/pybitty/branch/master/graph/badge.svg)](https://codecov.io/gh/the-forges/pybitty)

PyBitty is a memory unit conversion python module that makes working with multiple sizes and SI/IEC standards straight forward. It is based on unit ecapsulation, immutability, plugability, and testability: the idea that each unit should know how to operate with other valid units idempotently; every unit function returns a new unit or value, instead of changing itself; each unit implements interfaces so that it's easy to plug in new unit types (which also makes testing new unit types straight forward).

## Features

### Standards Compliance

- [ ] Full IEC Binary notation [SI 9th edition (page 145)](https://www.bipm.org/utils/common/pdf/si-brochure/SI-Brochure-9.pdf) compliance
- [ ] Full SI Decimal notation [SI 9th edition (page 145)](https://www.bipm.org/utils/common/pdf/si-brochure/SI-Brochure-9.pdf) compliance (**partial**)

### Mathematics

- [ ] Adding different units against each other
- [ ] Subtracting units from each other
- [ ] Multiplying units against each other
- [ ] Dividing units from each other

### Conversions

- [ ] Unit conversions
- [ ] Standard conversions

### Helpers

- [ ] Unit parsing
- [ ] Finding a specific unit

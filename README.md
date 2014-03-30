[SAGA](https://github.com/gsi-upm/SAGA)
=====
![GSI Logo](http://gsi.dit.upm.es/templates/jgsi/images/logo.png)

## Introduction
SAGA is a set of processing and linguistic resources, written in java, developed to run sentiment analysis over text using [GATE](http://gate.ac.uk) plataform.
Because of the nature of GATE, the text format should be plain or XML.

The sentiment analysis modules can be executed in two ways: in local mode using [GATE Developer](https://gate.ac.uk/family/developer.html) (project gate.sa.modules) or as a web service (project gate.sa.modules.web). 

## Getting started
Whether you intend to use this repository as an user or as a developer, you should download the last release of [GATE Developer](https://gate.ac.uk/family/developer.html) in order to run the graphic mode of this tool. You can find it in its [download page](https://gate.ac.uk/download/#latest). This download will include GATE Developer and Embedded and requires at least Java 6 update 10, 1.6.0_10, in order to be run.
If you are not familiar with GATE, check out these [training modules](https://gate.ac.uk/conferences/training-modules.html) to understand what GATE can do.

If you are a developer, you should know that in order to develop our own processing resources using GATE Embedded (GATE APIs), a suitable Java Development Environment is required. We strongly recommend using [Eclipse IDE for Java EE developers](http://www.eclipse.org/downloads/packages/eclipse-ide-java-ee-developers/keplersr1), because it's going to make easier the next configuration tasks.

## SAGA using GATE Developer
If you are not familiar with java coding and want to test our processing resources without touching a line of code, please read the following step by step guide of how to make a [Financial Sentiment Analyzer using GATE](https://github.com/gsi-upm/SAGA/wiki/Financial-Sentiment-Analyzer-using-GATE).

![Example](https://dl.dropboxusercontent.com/u/21681328/emoticonAndFinancial.png)

If you are a developer and want to explore how these processing resources work or make your own, please go to [IDE Configuration for gate.sa.modules](https://github.com/gsi-upm/SAGA/wiki/IDE-Configuration-for-gate.sa.modules)

## SAGA as a Web Service
We also offer our sentiment analyzers as a web service, in which you can input the text you want to be analyzed and receive the analysis results in marl format.



For more information about the processing and linguistic resources, sentiment analysis modules and examples, please check out our [Wiki](https://github.com/gsi-upm/SAGA/wiki) or contact us through: [http://gsi.dit.upm.es](http://gsi.dit.upm.es)

## Licenses

The source code on this repository is under the following licenses:

```
Copyright (c) 2014 GSI, UPM. All rights reserved.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
```

```
Copyright (c) 2013 GSI, UPM. All rights reserved.

Licensed under Lesser General Public License For Linguistic Resources; 
You may not use this repository and code except in compliance with the License. 
You may obtain a copy of the License at http://www.ida.liu.se/~sarst/bitse/lgpllr.html Unless required by 
applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific 
language governing permissions and limitations under the License.
```


In collaboration with Paradigma Tecnologico:
![Paradigma Logo](https://dl.dropboxusercontent.com/u/21681328/paradigma.png)


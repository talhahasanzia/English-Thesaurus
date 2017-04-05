[![deprecated](https://img.shields.io/badge/stability-deprecated-red.svg)]()
![version](https://img.shields.io/badge/version-outdated-red.svg)
[![Hex.pm](https://img.shields.io/hexpm/l/plug.svg)]()


This database contains 477,000+ English language words with their respective parts of speech entries.Those words which have more than 1 parts of speech usage are marked in columns PoS1, PoS2, PoS3 and PoS4.PoS1 column will always return some value (string), afterwards if a column entry is null that means it has no more parts of speech category. Sometimes ThesaurusDB does not work, so PartsOfSpeech can be used alternatively.




There are two rar files.
One is database file (includes .mdf and .ldf files).
One is Backup file (.bak file).
You can use either one of them.


These database are created using MSSQLS2008.


How To attach database file:
http://technet.microsoft.com/en-us/library/ms165673%28v=sql.105%29.aspx

How to restore backup:
http://msdn.microsoft.com/en-us/library/ms177429.aspx


LICENSE:

    Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

;;
;; Licensed to the Apache Software Foundation (ASF) under one
;; or more contributor license agreements.  See the NOTICE file
;; distributed with this work for additional information
;; regarding copyright ownership.  The ASF licenses this file
;; to you under the Apache License, Version 2.0 (the
;; "License"); you may not use this file except in compliance
;; with the License.  You may obtain a copy of the License at
;; 
;;   http://www.apache.org/licenses/LICENSE-2.0
;; 
;; Unless required by applicable law or agreed to in writing,
;; software distributed under the License is distributed on an
;; "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
;; KIND, either express or implied.  See the License for the
;; specific language governing permissions and limitations
;; under the License.
;;

# Qpid Dispatch 1.17.1 Release Notes

Dispatch is a lightweight AMQP 1.0 message router. More about
[Qpid
Dispatch]({{site_url}}/components/dispatch-router/index.html).

For more information about this release, including download links and
documentation, see the [release overview](index.html).


## Bugs fixed

 - [DISPATCH-2257](https://issues.apache.org/jira/browse/DISPATCH-2257) - listener with http=true uses AF_INTE6 even when ipv6 is not supported
 - [DISPATCH-2259](https://issues.apache.org/jira/browse/DISPATCH-2259) - server_name set by Dispatch Router contains illegal characters
 - [DISPATCH-2260](https://issues.apache.org/jira/browse/DISPATCH-2260) - http adaptor link remains after connector deletion on edge router
 - [DISPATCH-2261](https://issues.apache.org/jira/browse/DISPATCH-2261) - tcp adaptor link remains after connector deletion on edge router
 - [DISPATCH-2264](https://issues.apache.org/jira/browse/DISPATCH-2264) - [http2] Router crash on delete of httpListener
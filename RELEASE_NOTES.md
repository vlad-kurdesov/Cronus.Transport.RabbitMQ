#### 3.0.2 - 01.09.2017
* To be honest there is a problem in the public interface and the way we use endpoints has a memory leak unless you Open/Close the endpoint.

#### 3.0.1 - 01.12.2016
* Add setting for specifying admin port
* Adds a Virtual Host, if such not present in RabbitMQ, and assigning permissions for the user passed to the initial settings

#### 3.0.1-beta0002 - 01.12.2016
* Add setting for specifying admin port

#### 3.0.1-beta0001 - 01.12.2016
* Adds a Virtual Host, if such not present in RabbitMQ, and assigning permissions for the user passed to the initial settings

#### 3.0.0 - 08.09.2016
* Adds support for IScheduleMessages sent to pipelines
* Moves WithDefaultPublishersWithRabbitMq to Cronus
* Replaces RabbitMqEndpointPerBoundedContext with RabbitMqEndpointPerConsumer

#### 2.2.0 - 19.03.2016
* Schedule a message for future publishing is not possible using the 'rabbitmq_delayed_message_exchange' from http://www.rabbitmq.com/community-plugins.html
The plugin did not work well with the current RabbitMQ v3.5.3 so the RabbitMQ client is updated to the current latest v3.6.1

#### 2.1.3 - 06.07.2015
* Update packages

#### 2.1.2 - 02.07.2015
* Update packages

#### 2.1.1 - 02.07.2015
* Update packages

#### 2.1.0 - 02.07.2015
* Update packages

#### 2.0.1 - 25.05.2015
* Properly expose the configuration extensions

#### 2.0.0 - 16.05.2015
* Build for Cronus 2.*

#### 2.0.0-alpha04 - 15.05.2015
* Version for Cronus 2.0.alpha9

#### 1.2.6 - 21.04.2015
* Fix nuget package dependencies

#### 1.2.5 - 27.03.2015
* Fix issues with building exchanges and queues.

#### 1.2.4 - 25.03.2015
* Downgrade RabbitMq to v3.4.3

#### 1.2.3 - 23.03.2015
* Update to latest Cronus

#### 1.2.2 - 17.02.2015
* Improve error reporting.
* Update nuget packages

#### 1.2.1 - 13.01.2015
* Update Cronus package

#### 1.2.0 - 16.12.2014
* Add pipeline and endpoint strategies
* Fix bug when closing endpoint
* Fix bug with wrong endpoint for projections
* Fix bug with assigning wrong pipeline for app service endpoint
* Properly close rabbitMq channel

#### 1.0.3 - 02.10.2014
* Build for Cronus 1.1.40

#### 1.0.2 - 01.10.2014
* Build for Cronus 1.1.39 without ES publisher

#### 1.0.1 - 11.09.2014
* Fix bug with nuget package release

#### 1.0.0 - 21.06.2014
* Moved from Cronus repository

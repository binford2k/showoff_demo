# showoff_demo

This is just a very brief demo of some Showoff features. There are a couple quick ways to check it out.

* Install Showoff and run the presentation locally:
    * `gem install showoff`
    * `git clone https://github.com/binford2k/showoff_demo.git`
    * `cd showoff_demo`
    * `showoff serve`
* Run via the Docker image:
    * `docker run -p 9090:9090 binford2k/showoff showoff serve -u https://github.com/binford2k/showoff_demo.git`
    
In either case, once it's running browse to http://localhost:9090/presenter (or http://localhost:9090 for the audience view).

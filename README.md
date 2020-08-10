# quarks-meta


This uses https://github.com/mateodelnorte/meta

* https://github.com/cloudfoundry-incubator/quarks-operator
* https://github.com/cloudfoundry-incubator/quarks-job
* https://github.com/cloudfoundry-incubator/quarks-secret
* https://github.com/cloudfoundry-incubator/quarks-statefulset
* https://github.com/cloudfoundry-incubator/quarks-utils


* https://github.com/cloudfoundry-incubator/quarks-ci
* https://github.com/cloudfoundry-incubator/quarks-docs
* https://github.com/cloudfoundry-incubator/quarks-helm
* https://github.com/cloudfoundry-incubator/quarks-gora
* https://github.com/cloudfoundry-incubator/quarks-gora-release
* https://github.com/cloudfoundry-incubator/quarks-container-run
* https://github.com/viovanov/bosh-template-go


## Examples


```
meta git clone
meta git status
meta git checkout -b a-branch
meta exec "git apply $PWD/a.patch"
meta git commit -p -m "a message"
meta git push -u origin
meta gh pr ...
```

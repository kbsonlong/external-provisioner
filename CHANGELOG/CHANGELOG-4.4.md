# Release notes for v4.4.3

[Documentation](https://kubernetes-csi.github.io)

## Dependencies

### Added
_Nothing has changed._

### Changed
- github.com/kubernetes-csi/csi-lib-utils: [v0.14.0 → v0.14.1](https://github.com/kubernetes-csi/csi-lib-utils/compare/v0.14.0...v0.14.1)

### Removed
_Nothing has changed._

# Release notes for v4.4.2

[Documentation](https://kubernetes-csi.github.io)

# Changelog since v4.4.1

## Changes by Kind

### Bug or Regression

- Bump google.golang.org/grpc from v1.57.0 to v1.59.0 to fix CVE-2023-44487. ([#510](https://github.com/kubernetes-csi/external-attacher/pull/510), [@songjiaxun](https://github.com/songjiaxun))

## Dependencies

### Added
_Nothing has changed._

### Changed
- cloud.google.com/go/compute: v1.19.1 → v1.23.0
- github.com/envoyproxy/go-control-plane: [9239064 → v0.11.1](https://github.com/envoyproxy/go-control-plane/compare/9239064...v0.11.1)
- github.com/envoyproxy/protoc-gen-validate: [v0.10.1 → v1.0.2](https://github.com/envoyproxy/protoc-gen-validate/compare/v0.10.1...v1.0.2)
- github.com/golang/glog: [v1.1.0 → v1.1.2](https://github.com/golang/glog/compare/v1.1.0...v1.1.2)
- github.com/google/uuid: [v1.3.0 → v1.3.1](https://github.com/google/uuid/compare/v1.3.0...v1.3.1)
- golang.org/x/oauth2: v0.8.0 → v0.11.0
- golang.org/x/sync: v0.2.0 → v0.3.0
- google.golang.org/genproto/googleapis/api: dd9d682 → b8732ec
- google.golang.org/genproto/googleapis/rpc: 28d5490 → b8732ec
- google.golang.org/genproto: 0005af6 → b8732ec
- google.golang.org/grpc: v1.57.0 → v1.59.0
- google.golang.org/protobuf: v1.30.0 → v1.31.0

### Removed
_Nothing has changed._

# Release notes for v4.4.1

[Documentation](https://kubernetes-csi.github.io)

## Changes by Kind

### Uncategorized

- CVE fixes: CVE-2023-44487 ([#500](https://github.com/kubernetes-csi/external-attacher/pull/500), [@dannawang0221](https://github.com/dannawang0221))

## Dependencies

### Added
_Nothing has changed._

### Changed
- golang.org/x/crypto: v0.11.0 → v0.14.0
- golang.org/x/net: v0.13.0 → v0.17.0
- golang.org/x/sys: v0.10.0 → v0.13.0
- golang.org/x/term: v0.10.0 → v0.13.0
- golang.org/x/text: v0.11.0 → v0.13.0

### Removed
_Nothing has changed._

# Release notes for v4.4.0

[Documentation](https://kubernetes-csi.github.io)

# Changelog since v4.3.0

## Changes by Kind

### Feature

- Add --max-entries flag to limit ListVolumes request entries per page (#462, @kayrus)

### Uncategorized

- Update kubernetes dependencies to v1.28.0 (#475, @Sneha-at)

## Dependencies

### Added
- github.com/alecthomas/kingpin/v2: [v2.3.2](https://github.com/alecthomas/kingpin/v2/tree/v2.3.2)
- github.com/google/gnostic-models: [v0.6.8](https://github.com/google/gnostic-models/tree/v0.6.8)
- github.com/xhit/go-str2duration/v2: [v2.1.0](https://github.com/xhit/go-str2duration/v2/tree/v2.1.0)
- google.golang.org/genproto/googleapis/api: dd9d682
- google.golang.org/genproto/googleapis/rpc: 28d5490

### Changed
- cloud.google.com/go/compute: v1.15.1 → v1.19.1
- cloud.google.com/go: v0.105.0 → v0.34.0
- github.com/alecthomas/units: [f65c72e → b94a6e3](https://github.com/alecthomas/units/compare/f65c72e...b94a6e3)
- github.com/cenkalti/backoff/v4: [v4.1.3 → v4.2.1](https://github.com/cenkalti/backoff/v4/compare/v4.1.3...v4.2.1)
- github.com/cncf/xds/go: [06c439d → e9ce688](https://github.com/cncf/xds/go/compare/06c439d...e9ce688)
- github.com/envoyproxy/go-control-plane: [v0.10.3 → 9239064](https://github.com/envoyproxy/go-control-plane/compare/v0.10.3...9239064)
- github.com/envoyproxy/protoc-gen-validate: [v0.9.1 → v0.10.1](https://github.com/envoyproxy/protoc-gen-validate/compare/v0.9.1...v0.10.1)
- github.com/go-kit/log: [v0.2.0 → v0.2.1](https://github.com/go-kit/log/compare/v0.2.0...v0.2.1)
- github.com/go-logr/logr: [v1.2.3 → v1.2.4](https://github.com/go-logr/logr/compare/v1.2.3...v1.2.4)
- github.com/go-openapi/jsonreference: [v0.20.1 → v0.20.2](https://github.com/go-openapi/jsonreference/compare/v0.20.1...v0.20.2)
- github.com/go-task/slim-sprig: [348f09d → 52ccab3](https://github.com/go-task/slim-sprig/compare/348f09d...52ccab3)
- github.com/golang/glog: [v1.0.0 → v1.1.0](https://github.com/golang/glog/compare/v1.0.0...v1.1.0)
- github.com/google/gnostic: [v0.6.9 → v0.5.7-v3refs](https://github.com/google/gnostic/compare/v0.6.9...v0.5.7-v3refs)
- github.com/inconshreveable/mousetrap: [v1.0.1 → v1.1.0](https://github.com/inconshreveable/mousetrap/compare/v1.0.1...v1.1.0)
- github.com/kr/pretty: [v0.3.0 → v0.3.1](https://github.com/kr/pretty/compare/v0.3.0...v0.3.1)
- github.com/kubernetes-csi/csi-lib-utils: [v0.13.0 → v0.14.0](https://github.com/kubernetes-csi/csi-lib-utils/compare/v0.13.0...v0.14.0)
- github.com/moby/term: [39b0c02 → 1aeaba8](https://github.com/moby/term/compare/39b0c02...1aeaba8)
- github.com/onsi/ginkgo/v2: [v2.9.1 → v2.9.4](https://github.com/onsi/ginkgo/v2/compare/v2.9.1...v2.9.4)
- github.com/onsi/gomega: [v1.27.4 → v1.27.6](https://github.com/onsi/gomega/compare/v1.27.4...v1.27.6)
- github.com/prometheus/client_golang: [v1.14.0 → v1.16.0](https://github.com/prometheus/client_golang/compare/v1.14.0...v1.16.0)
- github.com/prometheus/client_model: [v0.3.0 → v0.4.0](https://github.com/prometheus/client_model/compare/v0.3.0...v0.4.0)
- github.com/prometheus/common: [v0.37.0 → v0.44.0](https://github.com/prometheus/common/compare/v0.37.0...v0.44.0)
- github.com/prometheus/procfs: [v0.8.0 → v0.10.1](https://github.com/prometheus/procfs/compare/v0.8.0...v0.10.1)
- github.com/spf13/cobra: [v1.6.0 → v1.7.0](https://github.com/spf13/cobra/compare/v1.6.0...v1.7.0)
- github.com/stretchr/testify: [v1.8.1 → v1.8.2](https://github.com/stretchr/testify/compare/v1.8.1...v1.8.2)
- go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp: v0.35.0 → v0.35.1
- go.uber.org/atomic: v1.7.0 → v1.10.0
- go.uber.org/goleak: v1.2.0 → v1.2.1
- go.uber.org/multierr: v1.6.0 → v1.11.0
- golang.org/x/crypto: 75b2880 → v0.11.0
- golang.org/x/exp: 6cc2880 → 509febe
- golang.org/x/lint: 738671d → d0100b6
- golang.org/x/net: v0.8.0 → v0.13.0
- golang.org/x/oauth2: v0.4.0 → v0.8.0
- golang.org/x/sync: 0de741c → v0.2.0
- golang.org/x/sys: v0.6.0 → v0.10.0
- golang.org/x/term: v0.6.0 → v0.10.0
- golang.org/x/text: v0.8.0 → v0.11.0
- golang.org/x/time: v0.2.0 → v0.3.0
- golang.org/x/tools: v0.7.0 → v0.8.0
- google.golang.org/genproto: 76db087 → 0005af6
- google.golang.org/grpc: v1.54.0 → v1.57.0
- google.golang.org/protobuf: v1.28.1 → v1.30.0
- honnef.co/go/tools: v0.0.1-2020.1.4 → ea95bdf
- k8s.io/api: v0.27.1 → v0.28.1
- k8s.io/apimachinery: v0.27.1 → v0.28.1
- k8s.io/client-go: v0.27.1 → v0.28.1
- k8s.io/component-base: v0.26.0 → v0.28.0
- k8s.io/csi-translation-lib: v0.27.1 → v0.28.1
- k8s.io/klog/v2: v2.90.1 → v2.100.1
- k8s.io/kube-openapi: 15aac26 → 2695361
- k8s.io/utils: a36077c → d93618c

### Removed
- cloud.google.com/go/accessapproval: v1.5.0
- cloud.google.com/go/accesscontextmanager: v1.4.0
- cloud.google.com/go/aiplatform: v1.27.0
- cloud.google.com/go/analytics: v0.12.0
- cloud.google.com/go/apigateway: v1.4.0
- cloud.google.com/go/apigeeconnect: v1.4.0
- cloud.google.com/go/appengine: v1.5.0
- cloud.google.com/go/area120: v0.6.0
- cloud.google.com/go/artifactregistry: v1.9.0
- cloud.google.com/go/asset: v1.10.0
- cloud.google.com/go/assuredworkloads: v1.9.0
- cloud.google.com/go/automl: v1.8.0
- cloud.google.com/go/baremetalsolution: v0.4.0
- cloud.google.com/go/batch: v0.4.0
- cloud.google.com/go/beyondcorp: v0.3.0
- cloud.google.com/go/bigquery: v1.44.0
- cloud.google.com/go/billing: v1.7.0
- cloud.google.com/go/binaryauthorization: v1.4.0
- cloud.google.com/go/certificatemanager: v1.4.0
- cloud.google.com/go/channel: v1.9.0
- cloud.google.com/go/cloudbuild: v1.4.0
- cloud.google.com/go/clouddms: v1.4.0
- cloud.google.com/go/cloudtasks: v1.8.0
- cloud.google.com/go/contactcenterinsights: v1.4.0
- cloud.google.com/go/container: v1.7.0
- cloud.google.com/go/containeranalysis: v0.6.0
- cloud.google.com/go/datacatalog: v1.8.0
- cloud.google.com/go/dataflow: v0.7.0
- cloud.google.com/go/dataform: v0.5.0
- cloud.google.com/go/datafusion: v1.5.0
- cloud.google.com/go/datalabeling: v0.6.0
- cloud.google.com/go/dataplex: v1.4.0
- cloud.google.com/go/dataproc: v1.8.0
- cloud.google.com/go/dataqna: v0.6.0
- cloud.google.com/go/datastore: v1.10.0
- cloud.google.com/go/datastream: v1.5.0
- cloud.google.com/go/deploy: v1.5.0
- cloud.google.com/go/dialogflow: v1.19.0
- cloud.google.com/go/dlp: v1.7.0
- cloud.google.com/go/documentai: v1.10.0
- cloud.google.com/go/domains: v0.7.0
- cloud.google.com/go/edgecontainer: v0.2.0
- cloud.google.com/go/errorreporting: v0.3.0
- cloud.google.com/go/essentialcontacts: v1.4.0
- cloud.google.com/go/eventarc: v1.8.0
- cloud.google.com/go/filestore: v1.4.0
- cloud.google.com/go/firestore: v1.9.0
- cloud.google.com/go/functions: v1.9.0
- cloud.google.com/go/gaming: v1.8.0
- cloud.google.com/go/gkebackup: v0.3.0
- cloud.google.com/go/gkeconnect: v0.6.0
- cloud.google.com/go/gkehub: v0.10.0
- cloud.google.com/go/gkemulticloud: v0.4.0
- cloud.google.com/go/gsuiteaddons: v1.4.0
- cloud.google.com/go/iam: v0.8.0
- cloud.google.com/go/iap: v1.5.0
- cloud.google.com/go/ids: v1.2.0
- cloud.google.com/go/iot: v1.4.0
- cloud.google.com/go/kms: v1.6.0
- cloud.google.com/go/language: v1.8.0
- cloud.google.com/go/lifesciences: v0.6.0
- cloud.google.com/go/logging: v1.6.1
- cloud.google.com/go/longrunning: v0.3.0
- cloud.google.com/go/managedidentities: v1.4.0
- cloud.google.com/go/maps: v0.1.0
- cloud.google.com/go/mediatranslation: v0.6.0
- cloud.google.com/go/memcache: v1.7.0
- cloud.google.com/go/metastore: v1.8.0
- cloud.google.com/go/monitoring: v1.8.0
- cloud.google.com/go/networkconnectivity: v1.7.0
- cloud.google.com/go/networkmanagement: v1.5.0
- cloud.google.com/go/networksecurity: v0.6.0
- cloud.google.com/go/notebooks: v1.5.0
- cloud.google.com/go/optimization: v1.2.0
- cloud.google.com/go/orchestration: v1.4.0
- cloud.google.com/go/orgpolicy: v1.5.0
- cloud.google.com/go/osconfig: v1.10.0
- cloud.google.com/go/oslogin: v1.7.0
- cloud.google.com/go/phishingprotection: v0.6.0
- cloud.google.com/go/policytroubleshooter: v1.4.0
- cloud.google.com/go/privatecatalog: v0.6.0
- cloud.google.com/go/pubsub: v1.27.1
- cloud.google.com/go/pubsublite: v1.5.0
- cloud.google.com/go/recaptchaenterprise/v2: v2.5.0
- cloud.google.com/go/recommendationengine: v0.6.0
- cloud.google.com/go/recommender: v1.8.0
- cloud.google.com/go/redis: v1.10.0
- cloud.google.com/go/resourcemanager: v1.4.0
- cloud.google.com/go/resourcesettings: v1.4.0
- cloud.google.com/go/retail: v1.11.0
- cloud.google.com/go/run: v0.3.0
- cloud.google.com/go/scheduler: v1.7.0
- cloud.google.com/go/secretmanager: v1.9.0
- cloud.google.com/go/security: v1.10.0
- cloud.google.com/go/securitycenter: v1.16.0
- cloud.google.com/go/servicecontrol: v1.5.0
- cloud.google.com/go/servicedirectory: v1.7.0
- cloud.google.com/go/servicemanagement: v1.5.0
- cloud.google.com/go/serviceusage: v1.4.0
- cloud.google.com/go/shell: v1.4.0
- cloud.google.com/go/spanner: v1.41.0
- cloud.google.com/go/speech: v1.9.0
- cloud.google.com/go/storage: v1.10.0
- cloud.google.com/go/storagetransfer: v1.6.0
- cloud.google.com/go/talent: v1.4.0
- cloud.google.com/go/texttospeech: v1.5.0
- cloud.google.com/go/tpu: v1.4.0
- cloud.google.com/go/trace: v1.4.0
- cloud.google.com/go/translate: v1.4.0
- cloud.google.com/go/video: v1.9.0
- cloud.google.com/go/videointelligence: v1.9.0
- cloud.google.com/go/vision/v2: v2.5.0
- cloud.google.com/go/vmmigration: v1.3.0
- cloud.google.com/go/vmwareengine: v0.1.0
- cloud.google.com/go/vpcaccess: v1.5.0
- cloud.google.com/go/webrisk: v1.7.0
- cloud.google.com/go/websecurityscanner: v1.4.0
- cloud.google.com/go/workflows: v1.9.0
- dmitri.shuralyov.com/gpu/mtl: 666a987
- github.com/BurntSushi/xgb: [27f1227](https://github.com/BurntSushi/xgb/tree/27f1227)
- github.com/OneOfOne/xxhash: [v1.2.2](https://github.com/OneOfOne/xxhash/tree/v1.2.2)
- github.com/alecthomas/template: [fb15b89](https://github.com/alecthomas/template/tree/fb15b89)
- github.com/buger/jsonparser: [v1.1.1](https://github.com/buger/jsonparser/tree/v1.1.1)
- github.com/cespare/xxhash: [v1.1.0](https://github.com/cespare/xxhash/tree/v1.1.0)
- github.com/docopt/docopt-go: [ee0de3b](https://github.com/docopt/docopt-go/tree/ee0de3b)
- github.com/flowstack/go-jsonschema: [v0.1.1](https://github.com/flowstack/go-jsonschema/tree/v0.1.1)
- github.com/go-gl/glfw/v3.3/glfw: [6f7a984](https://github.com/go-gl/glfw/v3.3/glfw/tree/6f7a984)
- github.com/go-gl/glfw: [e6da0ac](https://github.com/go-gl/glfw/tree/e6da0ac)
- github.com/go-kit/kit: [v0.9.0](https://github.com/go-kit/kit/tree/v0.9.0)
- github.com/go-stack/stack: [v1.8.0](https://github.com/go-stack/stack/tree/v1.8.0)
- github.com/google/martian/v3: [v3.0.0](https://github.com/google/martian/v3/tree/v3.0.0)
- github.com/google/martian: [v2.1.0+incompatible](https://github.com/google/martian/tree/v2.1.0)
- github.com/google/renameio: [v0.1.0](https://github.com/google/renameio/tree/v0.1.0)
- github.com/googleapis/gax-go/v2: [v2.0.5](https://github.com/googleapis/gax-go/v2/tree/v2.0.5)
- github.com/hashicorp/golang-lru: [v0.5.1](https://github.com/hashicorp/golang-lru/tree/v0.5.1)
- github.com/jstemmer/go-junit-report: [v0.9.1](https://github.com/jstemmer/go-junit-report/tree/v0.9.1)
- github.com/konsorten/go-windows-terminal-sequences: [v1.0.3](https://github.com/konsorten/go-windows-terminal-sequences/tree/v1.0.3)
- github.com/kr/logfmt: [b84e30a](https://github.com/kr/logfmt/tree/b84e30a)
- github.com/mitchellh/mapstructure: [v1.1.2](https://github.com/mitchellh/mapstructure/tree/v1.1.2)
- github.com/sirupsen/logrus: [v1.6.0](https://github.com/sirupsen/logrus/tree/v1.6.0)
- github.com/spaolacci/murmur3: [f09979e](https://github.com/spaolacci/murmur3/tree/f09979e)
- github.com/stoewer/go-strcase: [v1.2.0](https://github.com/stoewer/go-strcase/tree/v1.2.0)
- github.com/xeipuuv/gojsonpointer: [4e3ac27](https://github.com/xeipuuv/gojsonpointer/tree/4e3ac27)
- github.com/xeipuuv/gojsonreference: [bd5ef7b](https://github.com/xeipuuv/gojsonreference/tree/bd5ef7b)
- github.com/xeipuuv/gojsonschema: [v1.2.0](https://github.com/xeipuuv/gojsonschema/tree/v1.2.0)
- go.opencensus.io: v0.22.4
- golang.org/x/image: cff245a
- golang.org/x/mobile: d2bd2a2
- google.golang.org/api: v0.30.0
- gopkg.in/alecthomas/kingpin.v2: v2.2.6
- gopkg.in/errgo.v2: v2.1.0
- gotest.tools/v3: v3.0.3
- rsc.io/binaryregexp: v0.2.0
- rsc.io/quote/v3: v3.1.0
- rsc.io/sampler: v1.3.0
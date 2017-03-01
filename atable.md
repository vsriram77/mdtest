ERROR COUNT COMPARISION REPORT
===
file1 vs file2

| Name | Pre | Post | Diff | Per |
| :------ | :---: |  :---: |  :---: |  :---: |
| com.apple.cloud.umc.daemons.business.ingest.AppleTrailersIngest                           |     0 |     1 |     0 |     0 |
| com.apple.cloud.umc.dal.solr.CanonicalMediaSolrIndexer                                    |     0 |     1 |     0 |     0 |
| com.apple.cloud.umc.feedmanager.S3FeedFileStorageManager                                  |    29 |   168 |   139 | 479.31 |
| com.apple.cloud.umc.dal.CanonicalTvShowsRepository                                        |     1 |     4 |     3 | 300.00 |
| com.apple.its.imageservice.UmcImageServiceClient                                          |   292 |   335 |    43 |  14.73 |
| com.apple.cloud.umc.dal.cassolr.AbstractCassolrCanonicalRepository                        |    14 |    15 |     1 |   7.14 |
| com.apple.its.mediaservices.business.metadata.optimization.CastAndCrewOptimizer           |     1 |     1 |     0 |   0.00 |
| com.apple.its.mediaservices.business.mapping.matchmakers.AbstractMatchMaker               |    38 |    38 |     0 |   0.00 |
| com.apple.cloud.umc.dal.cassolr.CassandraCanonicalsRepository                             |     8 |     7 |    -1 | -12.50 |
| com.apple.cloud.umc.spec.feedvalidator.ValerieFeedValidator                               |   799 |   654 |  -145 | -18.15 |
| com.apple.cloud.umc.daemons.jobs.umc.Workflow                                             |    78 |    63 |   -15 | -19.23 |
| org.quartz.core.JobRunShell                                                               |    79 |    63 |   -16 | -20.25 |
| org.quartz.core.ErrorLogger                                                               |    79 |    63 |   -16 | -20.25 |
| com.apple.cloud.umc.spec.FeedManagerFeedFetcher                                           |   265 |   208 |   -57 | -21.51 |
| com.apple.its.mediaservices.business.metadata.workflow.BatchProcessor                     |     4 |     3 |    -1 | -25.00 |
| com.apple.cloud.umc.spec.catalog.BaseCatalogSpecFeedParser                                |     9 |     6 |    -3 | -33.33 |
| com.apple.cloud.umc.daemons.business.ingest.bridge.BridgeIngest                           |  1215 |   782 |  -433 | -35.64 |
| com.apple.cloud.umc.daemons.jobs.umc.AggregatedReportGenerator                            |   862 |   547 |  -315 | -36.54 |
| com.apple.its.mediaservices.business.mapping.TVStructureBuilder                           |     5 |     3 |    -2 | -40.00 |
| com.apple.cloud.umc.spec.catalog.v1r0.parser.CatalogSpecFeedParserV1_0                    |   255 |   102 |  -153 | -60.00 |
| com.apple.cloud.umc.daemons.business.ingest.bridge.ProtoWorkUnitHandler                   |   462 |   155 |  -307 | -66.45 |
| com.apple.cloud.umc.spec.availability.BaseAvailabilitySpecFeedParser                      |     8 |     2 |    -6 | -75.00 |
| com.apple.cloud.umc.externalcomm.combiner.CombinerPublisherImpl                           |  3556 |     0 |     0 |     0 |
| com.apple.itunes.combiner.feed.producer.kafka.AvroEntityFeedProducer                      |  3554 |     0 |     0 |     0 |
| com.apple.cloud.umc.spec.UmcSpecFeedFetcher                                               |   187 |     0 |     0 |     0 |
| com.apple.cloud.umc.daemons.business.ingest.TMSIngest                                     |    17 |     0 |     0 |     0 |
| com.apple.cloud.umc.util.TextNormalizer                                                   |    17 |     0 |     0 |     0 |
| com.apple.cloud.umc.daemons.business.ingest.netflix.NetflixCustomFeedIngester             |     4 |     0 |     0 |     0 |
| com.apple.cloud.umc.spec.PDRInfoProvider                                                  |     1 |     0 |     0 |     0 |

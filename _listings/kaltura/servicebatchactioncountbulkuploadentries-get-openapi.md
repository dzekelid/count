---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Batch Action Countbulkuploadentries
  description: Returns total created entries count and total error entries count
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/annotation_annotation/action/count:
    get:
      summary: Get Service Annotation Annotation Action Count
      description: count cue point objects by filter
      operationId: annotation.count
      x-api-path-slug: serviceannotation-annotationactioncount-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[codeEqual]
      - in: query
        name: filter[codeIn]
      - in: query
        name: filter[codeLike]
      - in: query
        name: filter[codeMultiLikeAnd]
      - in: query
        name: filter[codeMultiLikeOr]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[cuePointTypeEqual]
        description: 'Enum Type: `KalturaCuePointType`'
      - in: query
        name: filter[cuePointTypeIn]
      - in: query
        name: filter[descriptionLike]
      - in: query
        name: filter[descriptionMultiLikeAnd]
      - in: query
        name: filter[descriptionMultiLikeOr]
      - in: query
        name: filter[durationGreaterThanOrEqual]
      - in: query
        name: filter[durationLessThanOrEqual]
      - in: query
        name: filter[endTimeGreaterThanOrEqual]
      - in: query
        name: filter[endTimeLessThanOrEqual]
      - in: query
        name: filter[entryIdEqual]
      - in: query
        name: filter[entryIdIn]
      - in: query
        name: filter[eventTypeEqual]
        description: 'Enum Type: `KalturaEventType`'
      - in: query
        name: filter[eventTypeIn]
      - in: query
        name: filter[forceStopEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[freeText]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[isPublicEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[objectType]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[parentIdEqual]
      - in: query
        name: filter[parentIdIn]
      - in: query
        name: filter[partnerSortValueEqual]
      - in: query
        name: filter[partnerSortValueGreaterThanOrEqual]
      - in: query
        name: filter[partnerSortValueIn]
      - in: query
        name: filter[partnerSortValueLessThanOrEqual]
      - in: query
        name: filter[protocolTypeEqual]
        description: 'Enum Type: `KalturaAdProtocolType`'
      - in: query
        name: filter[protocolTypeIn]
      - in: query
        name: filter[questionLike]
      - in: query
        name: filter[questionMultiLikeAnd]
      - in: query
        name: filter[questionMultiLikeOr]
      - in: query
        name: filter[quizUserEntryIdEqual]
      - in: query
        name: filter[quizUserEntryIdIn]
      - in: query
        name: filter[startTimeGreaterThanOrEqual]
      - in: query
        name: filter[startTimeLessThanOrEqual]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaCuePointStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[subTypeEqual]
        description: 'Enum Type: `KalturaThumbCuePointSubType`'
      - in: query
        name: filter[subTypeIn]
      - in: query
        name: filter[systemNameEqual]
      - in: query
        name: filter[systemNameIn]
      - in: query
        name: filter[tagsLike]
      - in: query
        name: filter[tagsMultiLikeAnd]
      - in: query
        name: filter[tagsMultiLikeOr]
      - in: query
        name: filter[textLike]
      - in: query
        name: filter[textMultiLikeAnd]
      - in: query
        name: filter[textMultiLikeOr]
      - in: query
        name: filter[titleLike]
      - in: query
        name: filter[titleMultiLikeAnd]
      - in: query
        name: filter[titleMultiLikeOr]
      - in: query
        name: filter[triggeredAtGreaterThanOrEqual]
      - in: query
        name: filter[triggeredAtLessThanOrEqual]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: filter[userIdCurrent]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[userIdEqualCurrent]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[userIdEqual]
      - in: query
        name: filter[userIdIn]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Annotation
      - Annotation
      - Action
      - Count
  /service/baseentry/action/count:
    get:
      summary: Get Service Baseentry Action Count
      description: Count base entries by filter.
      operationId: baseEntry.count
      x-api-path-slug: servicebaseentryactioncount-get
      parameters:
      - in: query
        name: filter[accessControlIdEqual]
      - in: query
        name: filter[accessControlIdIn]
      - in: query
        name: filter[adminTagsLike]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[adminTagsMultiLikeAnd]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[adminTagsMultiLikeOr]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[assetParamsIdsMatchAnd]
      - in: query
        name: filter[assetParamsIdsMatchOr]
      - in: query
        name: filter[categoriesFullNameIn]
      - in: query
        name: filter[categoriesIdsEmpty]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[categoriesIdsMatchAnd]
      - in: query
        name: filter[categoriesIdsMatchOr]
        description: All entries of the categories, excluding their child categories
      - in: query
        name: filter[categoriesIdsNotContains]
      - in: query
        name: filter[categoriesMatchAnd]
      - in: query
        name: filter[categoriesMatchOr]
        description: All entries within these categories or their child categories
      - in: query
        name: filter[categoriesNotContains]
      - in: query
        name: filter[categoryAncestorIdIn]
        description: All entries within this categoy or in child categories
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
        description: This filter parameter should be in use for retrieving only entries
          which were created at Kaltura system after a specific time/date (standard
          timestamp format)
      - in: query
        name: filter[createdAtLessThanOrEqual]
        description: This filter parameter should be in use for retrieving only entries
          which were created at Kaltura system before a specific time/date (standard
          timestamp format)
      - in: query
        name: filter[creatorIdEqual]
      - in: query
        name: filter[documentTypeEqual]
        description: 'Enum Type: `KalturaDocumentType`'
      - in: query
        name: filter[documentTypeIn]
      - in: query
        name: filter[durationGreaterThanOrEqual]
      - in: query
        name: filter[durationGreaterThan]
      - in: query
        name: filter[durationLessThanOrEqual]
      - in: query
        name: filter[durationLessThan]
      - in: query
        name: filter[durationTypeMatchOr]
      - in: query
        name: filter[endDateGreaterThanOrEqualOrNull]
      - in: query
        name: filter[endDateGreaterThanOrEqual]
      - in: query
        name: filter[endDateLessThanOrEqualOrNull]
      - in: query
        name: filter[endDateLessThanOrEqual]
      - in: query
        name: filter[entitledUsersEditMatchAnd]
      - in: query
        name: filter[entitledUsersEditMatchOr]
      - in: query
        name: filter[entitledUsersPublishMatchAnd]
      - in: query
        name: filter[entitledUsersPublishMatchOr]
      - in: query
        name: filter[externalSourceTypeEqual]
        description: 'Enum Type: `KalturaExternalMediaSourceType`'
      - in: query
        name: filter[externalSourceTypeIn]
      - in: query
        name: filter[flavorParamsIdsMatchAnd]
      - in: query
        name: filter[flavorParamsIdsMatchOr]
      - in: query
        name: filter[freeText]
      - in: query
        name: filter[groupIdEqual]
      - in: query
        name: filter[hasMediaServerHostname]
      - in: query
        name: filter[idEqual]
        description: This filter should be in use for retrieving only a specific entry
          (identified by its entryId)
      - in: query
        name: filter[idIn]
        description: This filter should be in use for retrieving few specific entries
          (string should include comma separated list of entryId strings)
      - in: query
        name: filter[idNotIn]
      - in: query
        name: filter[isLive]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[isRecordedEntryIdEmpty]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[isRoot]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[lastPlayedAtGreaterThanOrEqual]
      - in: query
        name: filter[lastPlayedAtLessThanOrEqual]
      - in: query
        name: filter[limit]
      - in: query
        name: filter[mediaDateGreaterThanOrEqual]
      - in: query
        name: filter[mediaDateLessThanOrEqual]
      - in: query
        name: filter[mediaTypeEqual]
        description: 'Enum Type: `KalturaMediaType`'
      - in: query
        name: filter[mediaTypeIn]
      - in: query
        name: filter[moderationStatusEqual]
        description: 'Enum Type: `KalturaEntryModerationStatus`'
      - in: query
        name: filter[moderationStatusIn]
      - in: query
        name: filter[moderationStatusNotEqual]
        description: 'Enum Type: `KalturaEntryModerationStatus`'
      - in: query
        name: filter[moderationStatusNotIn]
      - in: query
        name: filter[nameEqual]
        description: This filter should be in use for retrieving entries with a specific
          name
      - in: query
        name: filter[nameLike]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[nameMultiLikeAnd]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[nameMultiLikeOr]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[objectType]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[parentEntryIdEqual]
      - in: query
        name: filter[partnerIdEqual]
        description: This filter should be in use for retrieving only entries which
          were uploaded by/assigned to users of a specific Kaltura Partner (identified
          by Partner ID)
      - in: query
        name: filter[partnerIdIn]
        description: This filter should be in use for retrieving only entries within
          Kaltura network which were uploaded by/assigned to users of few Kaltura
          Partners  (string should include comma separated list of PartnerIDs)
      - in: query
        name: filter[partnerSortValueGreaterThanOrEqual]
      - in: query
        name: filter[partnerSortValueLessThanOrEqual]
      - in: query
        name: filter[redirectFromEntryId]
        description: The id of the original entry
      - in: query
        name: filter[referenceIdEqual]
      - in: query
        name: filter[referenceIdIn]
      - in: query
        name: filter[replacedEntryIdEqual]
      - in: query
        name: filter[replacedEntryIdIn]
      - in: query
        name: filter[replacementStatusEqual]
        description: 'Enum Type: `KalturaEntryReplacementStatus`'
      - in: query
        name: filter[replacementStatusIn]
      - in: query
        name: filter[replacingEntryIdEqual]
      - in: query
        name: filter[replacingEntryIdIn]
      - in: query
        name: filter[rootEntryIdEqual]
      - in: query
        name: filter[rootEntryIdIn]
      - in: query
        name: filter[searchTextMatchAnd]
        description: 'This filter should be in use for retrieving specific entries
          while search match the input string within all of the following metadata
          attributes: name, description, tags, adminTags'
      - in: query
        name: filter[searchTextMatchOr]
        description: 'This filter should be in use for retrieving specific entries
          while search match the input string within at least one of the following
          metadata attributes: name, description, tags, adminTags'
      - in: query
        name: filter[sourceTypeEqual]
        description: 'Enum Type: `KalturaSourceType`'
      - in: query
        name: filter[sourceTypeIn]
      - in: query
        name: filter[sourceTypeNotEqual]
        description: 'Enum Type: `KalturaSourceType`'
      - in: query
        name: filter[sourceTypeNotIn]
      - in: query
        name: filter[startDateGreaterThanOrEqualOrNull]
      - in: query
        name: filter[startDateGreaterThanOrEqual]
      - in: query
        name: filter[startDateLessThanOrEqualOrNull]
      - in: query
        name: filter[startDateLessThanOrEqual]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaEntryStatus`This filter should be in use
          for retrieving only entries, at a specific {'
      - in: query
        name: filter[statusIn]
        description: This filter should be in use for retrieving only entries, at
          few specific {
      - in: query
        name: filter[statusNotEqual]
        description: 'Enum Type: `KalturaEntryStatus`This filter should be in use
          for retrieving only entries, not at a specific {'
      - in: query
        name: filter[statusNotIn]
        description: This filter should be in use for retrieving only entries, not
          at few specific {
      - in: query
        name: filter[tagsAdminTagsMultiLikeAnd]
      - in: query
        name: filter[tagsAdminTagsMultiLikeOr]
      - in: query
        name: filter[tagsAdminTagsNameMultiLikeAnd]
      - in: query
        name: filter[tagsAdminTagsNameMultiLikeOr]
      - in: query
        name: filter[tagsLike]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[tagsMultiLikeAnd]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[tagsMultiLikeOr]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[tagsNameMultiLikeAnd]
      - in: query
        name: filter[tagsNameMultiLikeOr]
      - in: query
        name: filter[totalRankGreaterThanOrEqual]
      - in: query
        name: filter[totalRankLessThanOrEqual]
      - in: query
        name: filter[typeEqual]
        description: 'Enum Type: `KalturaEntryType`'
      - in: query
        name: filter[typeIn]
        description: This filter should be in use for retrieving entries of few {
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: filter[userIdEqual]
        description: This filter parameter should be in use for retrieving only entries,
          uploaded by/assigned to a specific user (identified by user Id)
      - in: query
        name: filter[userIdIn]
      - in: query
        name: filter[userIdNotIn]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Baseentry
      - Action
      - Count
  /service/batch/action/countBulkUploadEntries:
    get:
      summary: Get Service Batch Action Countbulkuploadentries
      description: Returns total created entries count and total error entries count
      operationId: batch.countBulkUploadEntries
      x-api-path-slug: servicebatchactioncountbulkuploadentries-get
      parameters:
      - in: query
        name: bulkUploadJobId
        description: The id of the bulk upload job
      - in: query
        name: bulkUploadObjectType
        description: 'Enum Type: `KalturaBulkUploadObjectType`'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - CountBulkUploadEntries
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
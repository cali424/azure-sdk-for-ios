# --------------------------------------------------------------------------
#
# Copyright (c) Microsoft Corporation. All rights reserved.
#
# The MIT License (MIT)
#
# Permission is hereby granted, free of charge, to any person obtaining a copy
# of this software and associated documentation files (the ""Software""), to
# deal in the Software without restriction, including without limitation the
# rights to use, copy, modify, merge, publish, distribute, sublicense, and/or
# sell copies of the Software, and to permit persons to whom the Software is
# furnished to do so, subject to the following conditions:
#
# The above copyright notice and this permission notice shall be included in
# all copies or substantial portions of the Software.
#
# THE SOFTWARE IS PROVIDED *AS IS*, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
# IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
# FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
# AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
# LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
# FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
# IN THE SOFTWARE.
#
# --------------------------------------------------------------------------

use_frameworks!
platform :ios, '12.0'
workspace 'AzureSDK'

target 'AzureCommunication' do
  project 'sdk/communication/AzureCommunication/AzureCommunication'

  target 'AzureCommunicationTests' do
    inherit! :search_paths
  end
end

target 'AzureCommunicationChat' do
  project 'sdk/communication/AzureCommunicationChat/AzureCommunicationChat'

  target 'AzureCommunicationChatTests' do
    inherit! :search_paths
    pod 'OHHTTPStubs/Swift'
  end
  
  target 'AzureCommunicationChatUnitTests' do
    inherit! :search_paths
    pod 'OHHTTPStubs/Swift'
  end
end

target 'AzureCore' do
  project 'sdk/core/AzureCore/AzureCore'

  target 'AzureCoreTests' do
    inherit! :search_paths
  end
end

target 'AzureIdentity' do
  project 'sdk/identity/AzureIdentity/AzureIdentity'
  pod 'MSAL', '1.1.15'

  target 'AzureIdentityTests' do
    inherit! :search_paths
    pod 'MSAL', '1.1.15'
  end
end

target 'AzureStorageBlob' do
  project 'sdk/storage/AzureStorageBlob/AzureStorageBlob'
  pod 'MSAL', '1.1.15'

  target 'AzureStorageBlobTests' do
    inherit! :search_paths
    pod 'MSAL', '1.1.15'
  end
end

target 'AzureSDKDemoSwift' do
  project 'examples/AzureSDKDemoSwift/AzureSDKDemoSwift'
  pod 'MSAL', '1.1.15'
end

target 'AzureStorageBlobDemo' do
  project 'examples/AzureStorageBlobDemo/AzureStorageBlobDemo'
  pod 'MSAL', '1.1.15'
end

target 'AzureSDKDemoSwiftUI' do
  project 'examples/AzureSDKDemoSwiftUI/AzureSDKDemoSwiftUI'
  pod 'MSAL', '1.1.15'
end
